# CBT201
Converted to GitHub via [cbt2git](https://github.com/wizardofzos/cbt2git)
This is still a work in progress. GitHub repos will be deleted and created during this period...
~~~~~~~~~~~~~~~~

//***FILE 201 IS FROM BRUCE HULL OF BOEING COMPUTER SERVICES IN     *   FILE 201
//*           VIENNA, VIRGINIA, AND IS A CLIST USER EXIT IKJCT44B.  *   FILE 201
//*           THE PURPOSE OF THIS PARTICULAR EXIT IS TO EXTRACT     *   FILE 201
//*           OPERATING SYSTEM INFORMATION, SUCH AS LAST IPL DATE,  *   FILE 201
//*           AND PUT THESE THINGS INTO CLIST VARIABLES SO THEY     *   FILE 201
//*           CAN BE EASILY ACCESSED UNDER TSO.                     *   FILE 201
//*                                                                 *   FILE 201
//*        THIS PACKAGE ADDS CLIST VARIABLES THAT CONTAIN SYSTEM    *   FILE 201
//*        INFORMATION.  ONCE THESE VARIABLES HAVE BEEN ADDED TO    *   FILE 201
//*        YOUR SYSTEM, YOU CAN INQUIRE ON THEM WITH CLISTS AND     *   FILE 201
//*        UTILIZE OR DISPLAY THE SYSTEM INFORMATION.               *   FILE 201
//*                                                                 *   FILE 201
//*        FROM:  BRUCE HULL    M/S CV-34                           *   FILE 201
//*               BOEING COMPUTER SERVICES                          *   FILE 201
//*               7990 BOEING CT.                                   *   FILE 201
//*               VIENNA, VA 22182-3999                             *   FILE 201
//*               (703) 847-1187                                    *   FILE 201
//*               NASPA: HULLBRUR                                   *   FILE 201
//*                                                                 *   FILE 201
//*        SUBMISSION:  MVS TSO/E MODULE IKJCT44B - TSO/E           *   FILE 201
//*                     INSTALLATION-WRITTEN BUILT-IN FUNCTION      *   FILE 201
//*                                                                 *   FILE 201
//*        MODULE IKJCT44B PROVIDES THE FOLLOWING CLIST VARIABLES:  *   FILE 201
//*                                                                 *   FILE 201
//*        &SYSXACCT        CONTAINS THE ACCOUNT NUMBER USED TO     *   FILE 201
//*                         LOGON TO TSO.                           *   FILE 201
//*        &SYSXCPUH        CONTAINS THE NUMBER OF CPU SECONDS      *   FILE 201
//*                         USED DURING SESSION IN FORM SECONDSHH.  *   FILE 201
//*        &SYSXCPUTYPE     CONTAINS THE MACHINE TYPE OF THE CPU    *   FILE 201
//*                         THIS TSO SESSION IS EXECUTING ON.       *   FILE 201
//*        &SYSXDFP         CONTAINS THE LEVEL OF THE DFP PRODUCT   *   FILE 201
//*                         INSTALLED ON THE SYSTEM IN FORM VRRM.   *   FILE 201
//*        &SYSXIPLAT       CONTAINS THE DATE AND TIME OF THE       *   FILE 201
//*                         LAST IPL OF THE OPERATING SYSTEM.       *   FILE 201
//*        &SYSXLU          CONTAINS THE LU NAME (TERMINAL ID)      *   FILE 201
//*                         OF THE TERMINAL BEING USED OR NULL.     *   FILE 201
//*        &SYSXMVS         CONTAINS THE NAME AND SMP FUNCTION ID   *   FILE 201
//*                         OF THE MVS OPERATING SYSTEM BEING       *   FILE 201
//*                         USED.                                   *   FILE 201
//*        &SYSXRES         CONTAINS THE VOLUME SERIAL NUMBER OF    *   FILE 201
//*                         THE SYSTEM RESIDENCE VOLUME (SYSRES).   *   FILE 201
//*        &SYSXSERIAL      CONTAINS THE MACHINE SERIAL NUMBER OF   *   FILE 201
//*                         THE CPU THIS TSO SESSION IS EXECUTING   *   FILE 201
//*                         ON.                                     *   FILE 201
//*        &SYSXSMFID       CONTAINS THE SMF ID OF THE MVS          *   FILE 201
//*                         OPERATING SYSTEM THIS TSO SESSION       *   FILE 201
//*                         EXECUTING ON.                           *   FILE 201
//*                                                                 *   FILE 201
//*        MEMBERS OF THE PDS:                                      *   FILE 201
//*                                                                 *   FILE 201
//*        ASM        JCL USED TO ASSEMBLE THE OBJECT DECK          *   FILE 201
//*                   OBJCT44B.                                     *   FILE 201
//*        IKJCT44B   ASM DECK OF IKJCT44B.                         *   FILE 201
//*        OBJCT44B   OBJECT DECK OF IKJCT44B.                      *   FILE 201
//*        SESSION    A CLIST USED TO DEMONSTRATE USE OF THE NEW    *   FILE 201
//*                   VARIABLES.                                    *   FILE 201
//*        SYSTEM     A CLIST USED TO DEMONSTRATE USE OF THE NEW    *   FILE 201
//*                   VARIABLES.                                    *   FILE 201
//*        TS40084    A SMP/E USERMOD USED TO APPLY MOD IKJCT44B.   *   FILE 201
//*        VARIABLE   A SHORT DESCRIPTION OF ALL CLIST VARIABLES.   *   FILE 201
//*                   CAN BE USED FOR TSO HELP WITH THE HEL         *   FILE 201
//*                   COMMAND FROM FILE 134.                        *   FILE 201
//*                                                                 *   FILE 201
~~~~~~~~~~~~~~~~

