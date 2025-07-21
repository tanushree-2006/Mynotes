# Day-1
Welcome to my repository
# Day-2
I am still facing errors while downloading Kali Linux on my macOS. Unzipping the file is creating additional problems for me. I will make sure to download and set it up properly before the next class so that I can avoid these issues during the session.
# Day-3
I downloaded Kali Linux for VirtualBox using this method, which helped me download it without any errors.
1. Install Kali Linux using VirtualBox (Recommended for Mac users)

Step 1. Install VirtualBox

1. Go to [VirtualBox Downloads](https://www.virtualbox.org/wiki/Downloads).
2. Click “OS X hosts” to download the macOS installer.
3. Open the downloaded `.dmg` file and follow the installation instructions.

Step 2. Download Kali Linux VirtualBox Image

1. Visit the official Kali Linux Virtual Images page:
   [Kali Linux VirtualBox Images](https://www.kali.org/get-kali/#kali-virtual-machines).
2. Under “Kali Linux VirtualBox Images”, click Download for your architecture (usually `amd64`).
3. The file will be in .7z format.

Step 3. Extract the Downloaded .7z File

1. Download and install Keka from [Keka.io](https://www.keka.io/en/) if not installed.
2. Right-click the `.7z` file → Open With → Keka → It will extract to a `.vbox` and `.vmdk` or `.vdi` file.

Step 4. Import Kali Linux into VirtualBox

1. Open VirtualBox.
2. Click “File” → “Import Appliance…”.
3. Select the extracted `.ova` file if available, or create a new VM:

   * Click New → name it Kali Linux.
   * Choose Linux → Debian (64-bit) as type and version.
   * Allocate at least 2GB RAM (2048 MB) and 2 CPUs for smooth performance.
   * When asked for virtual hard disk, choose “Use existing virtual hard disk file”, and browse to the extracted Kali image.

Step 5. Start Kali Linux

1. Click Start in VirtualBox.
2. Login with default credentials:

   * Username:kali
   * Password:kali

Important Notes

* Ensure at least 30GB free space on your Mac for smooth VM operation.
* If you face Security Blocked error during VirtualBox installation:

  * Go to System Preferences → Security & Privacy → General tab and click Allow for Oracle.
* Always download only from official Kali Linux and VirtualBox websites to avoid malicious files.

Alternative: Installing Kali directly on Mac (Advanced Users)

* You can dual boot or use ARM images for M1/M2 Macs, but this requires partitioning and is riskier. VirtualBox is safest for class practice.

