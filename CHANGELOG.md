## 1.4.0 (July 6, 2020)
    * Update component to new sailor version 2.6.10
    * If deleting a file that does not exist, emit the empty message.
    * Use POSIX rename if possible to move files. It is now possible to replace existing files with move.
    * Update all dependencies.
    * Use Node v 14.
    * Remove update docs on deploy script

## 1.3.0 (June 5, 2020)

    * Add new 'Move File' action
    * Fix performance problem when trying to download large number of files

## 1.2.2 (May 19, 2020)

    * Update component to new sailor version 2.6.7

## 1.2.1 (December 30, 2019)

    * Update component to new sailor version 2.5.4

# 1.2.0 (December 18, 2019)
## General Changes
    * Add max to file size and environment variable to configure
    * Add key-based authentication
    * Add Download files action
    * Add Upload File From URL action    
    * The following actions are renamed:
      - Upload files -> Upload files From Attachments Header
      - Lookup file by name -> Download file by name
      - Get new and updated files -> Poll files

# 1.1.2 (December 6 2019)

## General Changes
    * New Action: Download files
    * Migrate integration tests to another SFTP Server
    * Fix integration tests error during local running
    * Migrate SFTP-->Attachment upload logic to streams
    
## Actions
### Poll files
    * Fix 0kb file download bug  
### Action: Download file by name
    * Fix 0kb file download bug  

    
# 1.1.1 (December 6 2019)

## General Changes
    * Add Lookup files action

# 1.1.0 (December 5, 2019)

## General Changes
    * Add `Delete file` action
    * Add `Lookup file by name` action
    * Add `Get new and updated files` trigger

## Actions

### Upload files
       * Add custom name for uploaded file

# 1.0.0 (October 8, 2019)
    * Initial release
    * Add custom port field instead of defaulting to 22
    * Add more unit tests
    * Fix integration test using `path.resolve` based on test machine
    * Format repository according to Airbnb styling
