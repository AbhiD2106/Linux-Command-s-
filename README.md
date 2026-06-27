# Check current directory
pwd

# List files
ls
ls -a
ls -l
ls -lh
ls -lha

# Print current directory
cd

# Navigate directories
cd TDPCL
cd ..

# Create a new directory
mkdir cmd_commands

# Verify
ls

# Enter directory
cd cmd_commands

# Check contents
ls

# Go back
cd ..

# Verify
ls

# Enter again
cd cmd_commands

# Create an empty directory
mkdir demo

# Verify
ls

# Remove empty directory
rmdir demo

# Verify
ls

# (Assume mytxt.txt already exists)

# Verify files
ls

# Copy file into demo directory
cp mytxt.txt demo

# Verify
ls

# Enter demo directory
cd demo

# Verify copied file
ls

# Delete copied file
rm mytxt.txt

# Verify
ls

# Go back
cd ..

# Verify
ls

# Move file into demo directory
mv mytxt.txt demo

# Enter demo
cd demo

# Move file back to parent directory
mv mytxt.txt ..

# Verify
ls

# Create directory
mkdir cmds

# Verify
ls

# Remove directory recursively
rm -r cmds

# Verify
ls

# Assume filee.txt exists

# Move file to parent directory
mv filee.txt ..

# Go back
cd ..

# Rename file
mv filee.txt myfile.txt

# Verify
ls

# Display file
cat myfile.txt

# Create file
cat > abhi.txt
hello im abhi
# Press Ctrl + D

# Display file
cat abhi.txt

# List files
ls

# Display all text files
cat *.txt

# Create copy.txt
cat > copy.txt
this is copy file
# Press Ctrl + D

# Create paste.txt
cat > paste.txt
this is paste file
# Press Ctrl + D

# Overwrite paste.txt
cat copy.txt > paste.txt

# Verify
cat copy.txt
cat paste.txt

# Recreate paste.txt
cat > paste.txt
this is paste file
# Press Ctrl + D

# Append
cat copy.txt >> paste.txt

# Verify
cat paste.txt

# Merge files
cat copy.txt paste.txt > merge.txt

# Verify
cat merge.txt

# Disk usage
du
du -h

# Search text
grep abhi abhi.txt
grep copy copy.txt
grep abhi *.txt

# Clear terminal
clear

# Exit terminal
exit
