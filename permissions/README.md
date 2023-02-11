# 0-iam_betty: switches the current user to the user betty
# 1-who_am_i: prints the effective ussername of the current user
# 2-groups: prints all the groups the current user is part of
# 3-new_owner: changes the owner of the file hello to the user betty
# 4-empty: creates an empty file named hello
# 5-execute: adds execute permissions to the owner of the file hello
# 6-multiple_permissions: adds execute permissions to the owner and group owner, and read permissions to all users
# 7-everybody: adds execute permissions to the owner, the group owner and the other users, to the file hello
# 8-James_Bond: gives the owner and the group owner no permissions, and all permissions to other users
# 9-John_Doe: changes permissions for hello to -rwxr-x-wx
# 10-mirror_permissions: sets permissions for hello the same as olleh
# 11-directories_permissions: adds execute permissions to all subdirectories of the current directory to owner, group owner and all users (not regular files)
# 12-directory_permissions: creates my_dir directory with 751 permissions
# 13-change_group: changes group owner to school for hello
# 14-change_owner_and_group: changes owner to vincent and group owner to staff for all files and directories in the current directory
# 15-symbolic_link_permissions: changes the owner to vincent and the group owner to staff for _hello
# 16-if_only: changes the owner of hello to vincent only if it is owned by guillaume
