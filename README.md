# Error-message-prank-on-linux

# Prank Project

This project contains a simple script that displays a prank error message.

## Installation

To install and use the prank script, follow these steps:

1. Ensure `zenity` is installed on your system. You can install it using the following commands:

### For Debian-based systems (like Ubuntu):
    sudo apt-get install zenity

### For Red Hat-based systems (like Fedora):
    sudo yum install zenity

2. Create a new file named `prank_script.sh`:
    nano prank_script.sh

3. Add the following content to `prank_script.sh`:

    #!/bin/bash

    # Show error message using zenity
    zenity --error --text="YOU HAVE BEEN PRANKED"

4. Save and close the file.

5. Make the prank script executable:
    chmod +x prank_script.sh

6. Run the script:
    ./prank_script.sh

## Prank Script

The prank script uses `zenity` to display a prank error message.

### Script Content

Here is the content of the `prank_script.sh` file:

    #!/bin/bash

    # Show error message using zenity
    zenity --error --text="YOU HAVE BEEN PRANKED"

## License

This project is licensed under the MIT License.
