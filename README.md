# Task

Identify the 3 major vulnerabilities in this applications backend.

A previous intern tried to fix it, by renaming files to some UUID.randomUUID() and fully ignores the submitted file name.

You might want to look at 
* `/backend/src/main/java/com/challenge/drive/controller`
* `backend/src/main/java/com/challenge/drive/service/ClamAVService.java`
* `main/backend/src/main/java/com/challenge/drive/dto/RemoteUploadDto.java`
* `main/backend/src/main/java/com/challenge/drive/util/ResetPasswordToken.java`

If you have found them, write a small test to verify the intended behaviour before changing it.

Then fix these issues, and write into the commit message what the problem was.
