# Create the file
sudo touch /home/demo.txt

# Set permissions (Any other user can read it, group can read/write & owner can read/write/execute it)
sudo chmod 764 /home/demo.txt

# Verify
ls -l /home/demo.txt
