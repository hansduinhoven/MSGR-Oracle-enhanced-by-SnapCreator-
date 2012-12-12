MSGR-Oracle-enhanced-by-SnapCreator-
====================================

Dear list,

We need a solution for improving SnapManager for Oracle functionality. 
1 
With SnapManager 3.2 for Oracle there is not a "recent" snapshot created, so the backup program does not recognize te latest
snapshot. Currently snapshots are to be manually, in order to make backups with the most actual snapshots.
2
Customer has more than one databases per LUN, where each database has it's own profile. 
Backup to tape with Backup Exec cannot work with more databases i.e. more profiles per LUN.

TR-3761 shows, that it is mandatory, to make a profile per database.

The SMG for Oracle admin guide page 118 states, that every snapshot needs a variable "smid".
"The SnapManager unique ID is the only required element when creating a name for the Snapshot
copy. This ID ensures that you create a unique Snapshot name"
So here it is not possible to have the snapshot name or extension ending on "recent", like you can do in 
SnapManager for SQL or Exchangte. 

Does SnapCreator offer here added functionality, so the snapshot name will get the desired name?

Thanks for helping.

Cheers,

Hans Duinhoven
