<h1>Python For Sysadmins Cheat Sheet</h1>
<h3>OS Module</h3>
<p><b>os.sep</b><br> gives the current working directory as the sting
value.
<p><b>os.getcwd()</b><br> gives the current working directory as the sting
value
<p><b>os.chdir("Dir loc")</b><br> takes in directory location and changes the
working directory
<p><b>os.listdir("filename")</b><br> gives s the list of all the files.
<p><b>os.makedirs</b><br>("foldernames")
creates the folders.
<p><b>os.unlink("filename")</b><br> deletes a file
<p><b>os.rmdir("folder")</b><br> deletes a folder.
<p><b>os.walk("folder name")</b><br> this returns foldername, subfolders and files sin it for foldername, subfoldername, filename in os.walk("."):<br>
... print(foldername, subfoldername, filename)
<h3>os.path module</h3>
<p><b>os.path.join ("folder1", "folder2","folder3", "filename")</b><br>
This takes the folder list and joins them to give a path name
<p><b>os.path.abspath("filename")</b><br> this gives the absolute path of the file
<p><b>os.path.isabs("filepath")</b><br> gives true of false for the abs path
<p><b>os.path.relpath("filepath")</b><br> gives relative path for the 2 paths
you give.
<p><b>os.path.exists("Filename")</b><br> gives true or false for the file name
<p><b>os.path.isfile("filepath") </b><br>true if the path is file
<p><b>os.path.isdir("filepath")</b><br> true if the path is folder
<p><b>os.path.getsize("filename")</b><br> gives the size in bytes

<h3>shutil</h3>
<p><b>shutil.copy("source", "destination")</b><br> Copies source file to
destination file
<p><b>shutil.copytree("source_folder","destination_Folder")</b><br>
useful for backups
<p><b>shutil.move("source_folder","destination_folder")</b><br>
This can also be used as renaming option.
<p><b>shutil.rmtree("dir_name")</b><br> To delete a full directory we use
this


