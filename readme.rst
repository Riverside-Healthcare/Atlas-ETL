..
    Atlas of Information Management
    Copyright (C) 2020  Riverside Healthcare, Kankakee, IL

    This program is free software: you can redistribute it and/or modify
    it under the terms of the GNU General Public License as published by
    the Free Software Foundation, either version 3 of the License, or
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,
    but WITHOUT ANY WARRANTY; without even the implied warranty of
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License
    along with this program.  If not, see <https://www.gnu.org/licenses/>.

|docs|

Atlas ETL
=========

The Atlas ETL (designed for use with the `Atlas web application <https://github.com/Riverside-Healthcare/Atlas>`_), is used to collect report metadata from a variety of sources and merge it into a common database.

There are two primary ETLs -

- Report Metadata
- Report Run Data

The ETL's are both SSIS packages which are scheduled to run as jobs on a Microsft SQL Server. The metadata ETl can be scheduled to run at a fairly frequent interval - every 15 minutes - hour, while the run data ETL can be run daily.



Credits
-------


Atlas ETL was created by the Riverside Healthcare Analytics team -

* Paula Courville
* `Darrel Drake <https://www.linkedin.com/in/darrel-drake-57562529>`_
* `Dee Anna Hillebrand <https://github.com/DHillebrand2016>`_
* `Scott Manley <https://github.com/Scott-Manley>`_
* `Madeline Matz <mailto:mmatz@RHC.net>`_
* `Christopher Pickering <https://github.com/christopherpickering>`_
* `Sean Pickering <https://github.com/Sean-Pickering>`_
* `Dan Ryan <https://github.com/danryan1011>`_
* `Richard Schissler <https://github.com/schiss152>`_
* `Eric Shultz <https://github.com/eshultz>`_



   

.. |docs| image:: https://img.shields.io/badge/Atlas_ETL-Documentation-orange
   :target: https://riverside-healthcare.github.io/Atlas-ETL/
