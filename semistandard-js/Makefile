# Makefile

# Define the file you want to make executable and move
FILE = js

# Define the destination directory
DEST_DIR = /bin

# The default target: make the file executable and move it to /bin
all: make_executable move_to_bin

# Target to make the file executable
make_executable:
	chmod +x $(FILE)

# Target to move the file to /bin (requires sudo)
move_to_bin: make_executable
	sudo mv $(FILE) $(DEST_DIR)

# Clean up the build files
clean:
	rm -f $(DEST_DIR)/$(FILE)
