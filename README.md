# Google-Drive-Uploader #
Google Drive Uploader by Maskoid.
You can upload files &amp; directory to google drive.

## How to use ##
* Create your Google Drive API from https://console.developers.google.com or you can search on google about API

* Download and run google-drive-uploader.sh , Frist time script can ask you about Google Drive API Client ID & Client secret key, type for keys on there and follow instructions.

* You can use google-drive-uploader.sh file below options:- 


-C | --create-directory/folder <folder-name> - option to create directory/folder with folder id.

-r | --dir-id <googledrive-folderID> - google folder id to which the file/directory to upload. ( You can find your google drive folder id on address bar on G-drive )

-v | --folder-id - Display Folder ID

-z | --config - Override default config file with custom config file.

-h | --help - Display usage instructions.

## Example:-  ##

* If you want to create folder then :- bash google-drive-uploader.sh -C [ Folder-Name ]

* If you want to create folder and show folder id then :- bash google-drive-uploader.sh -v -C [ Folder-Name ]

* If you want to add files on Google Drive folder then :- bash google-drive-uploader.sh -r [ Folder ID ] [ Full path of files which you upload ]


## How to download ##
Connect to your server as root via SSH

    ssh root@your.server

Download the installation script

    curl -O https://maskoid.net/data/google-drive-uploader.sh 

Then run it

    bash google-drive-uploader.sh [ Your Option ]

Credit

[Maskoid Technologies Pvt. Ltd.](https://www.maskoid.com) | [Google Cloud Platform ](https://console.developers.google.com) | [GitHub](https://gihub.com)

Thanks for visting ! Happy coding.

![alt text](https://maskoid.net/img/shubham.png "Shubham The DevOps")

[www.shubhamthedevops.com](https://shubhamthedevops.com)

