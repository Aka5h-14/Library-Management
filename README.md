## DFD 0
      
      +----------------------------------+
      |            Admin                 |
      |                                  |
      |  - Manage Books                  |  
      |  - Manage Students               |
      +----------------------------------+
                |
                |               +-------------------------+
                |               |   Library Management     |
                +-------------->|        System (LMS)      |<------------------+
                                |                          |                   |
                                +--------------------------+                   |
                                                ^                               |
                                                |                               |
                                      +---------+---------+          +-----------------------+
                                      |      Books        |          |       Students         |
                                      +-------------------+          |                       |
                                                                      +-----------------------+

## DFD 1
      +----------------------------------+
      |          Admin Login             |
      |                                  |
      |  - Input: Username, Password     |
      |  - Output: Login success/failure |
      +----------------------------------+
                    |
                    v
      +----------------------------------+
      |         Manage Books             |
      |                                  |
      |  - Add, Update, Delete Books     |
      +----------------------------------+
                    |
                    v
      +----------------------------------+            +-------------------------+
      |       Manage Students            |------------|    Issue Books          |
      |                                  |            |                         |
      +----------------------------------+            +-------------------------+
                    |
                    v
      +----------------------------------+
      |        View Issued Books         |
      +----------------------------------+
                    |
                    v
      +----------------------------------+
      |          View Books              |
      +----------------------------------+
                    |
                    v
      +----------------------------------+
      |        Library Database          |
      +----------------------------------+
