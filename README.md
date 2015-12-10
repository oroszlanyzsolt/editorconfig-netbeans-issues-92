# editorconfig-netbeans-issues-92

Steps to reproduce the error is:
1) Download project from GitHub
2) Open both index.php from both project-1 and project-2 (see everything is ok yet)
3) Place the editorconfig.txt to project-2 or project-1; not both becuase it will be obvious why the other project inherit settings, place the editorconfig.txt on project-2 and rename it to .editorconfig
4) Write something both projects index.php ( I have auto formating enabled on save) and save it

Now you can see both project gets save according project-2 .editorconfig; this should not happen, only project-2 index.php should have the effect of .editorconfig. What makes it worst I thing project settings is not affacted at all but the global formating are effected!
