Introduction to DevOps
DevOps is a set of practices that combines software development (Dev) and IT operations (Ops). It aims to shorten the systems development life cycle while delivering features, fixes, and updates frequently in close alignment with business objectives.
Key Principles of DevOps
Continuous Integration (CI)

Regular code integration
Automated testing
Early bug detection
Continuous Delivery (CD)

Automated deployment
Frequent releases
Reliable delivery process
Basic Navigation
Directory Navigation

cd /path/to/directory    # Change directory
cd ..                    # Go up one level
cd ~                     # Go to home directory
cd -                     # Go to previous directory
Examples:

cd /home/user/documents  # Navigate to documents folder
cd ..                    # Move up to parent directory
cd ~/Downloads          # Go to Downloads in home directory
cd -                    # Return to previous directory
File Operations

ls                       # List files
ls -l                    # Detailed list
ls -a                    # Show hidden files
ls -h                    # Human-readable sizes
Examples:

ls                      # Show all files
ls -l                   # Show detailed list with permissions
ls -la                  # Show all files including hidden ones
ls -lh                  # Show sizes in human-readable format
ls *.txt                # Show only text files
File Management

cp file1 file2          # Copy files
mv file1 file2          # Move/rename files
rm file                 # Remove file
mkdir directory         # Create directory
rmdir directory         # Remove directory
Examples:

cp document.txt backup.txt           # Copy file
cp -r folder1 folder2                # Copy directory recursively
mv oldname.txt newname.txt           # Rename file
mv file.txt /path/to/destination/    # Move file
rm file.txt                          # Remove file
rm -rf directory                     # Remove directory and contents
mkdir new_project                    # Create directory
mkdir -p parent/child/grandchild     # Create nested directories
rmdir empty_directory                # Remove empty directory
Command History
history                   # Show command history
!n                       # Execute nth command
!!                       # Execute last command
Ctrl + R                 # Search command history
Examples:

history | grep cd        # Show all cd commands in history
!5                       # Execute command number 5 from history
!!                       # Repeat last command
!$                       # Use last argument of previous command
Command Completion
Tab key for file/directory completion
Double tab for options
Path completion
