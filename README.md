# Steps To Install Docker on MAC

## Overview
This is a step-by-step guide to help you install Docker on mac OS.  <br> <br>
To Install Docker on MAC, we're going to be installing "Docker for Desktop" 

### Step 1: Check Your Mac’s Compatibility
Before diving into the installation process, ensure your Mac meets the necessary requirements to run Docker. Docker Desktop for Mac is compatible with macOS El Capitan 10.11 and newer versions. It’s also important to note that Docker runs natively on Mac systems that use the Apple silicon chip or Intel chip. Checking your Mac’s compatibility is crucial for a smooth installation process.  

Also, ensure your mac has at least 4GB of RAM .

### Step 2: Download Docker Desktop for Mac
To get started, you need to download the Docker Desktop application. Here’s how:

- Go to the [Docker Hub website](hub.docker.com).
- If youdon’t have a Docker account, you’ll need to create one. Click on “Sign Up” and follow the registration process.
  <br>
 <br> <img width="1512" alt="Screenshot 2024-11-02 at 20 01 30" src="https://github.com/user-attachments/assets/54aab072-88ff-4fe3-9b85-743743be0fbf"> <br>
  <br>
- Once you have an account, log in and head to the “Docker Desktop” section. <br>
  <br> <img width="1512" alt="Screenshot 2024-11-02 at 20 14 43" src="https://github.com/user-attachments/assets/883bda6c-ff10-4bc9-8168-51153ba6d5f4">
 <br>
<br>

- Select “Docker Desktop for Mac” and choose the version compatible with your Mac (either for Intel chips or Apple silicon).  
  <br> <img width="1512" alt="Screenshot 2024-11-02 at 20 17 36" src="https://github.com/user-attachments/assets/9340dc05-6d17-4deb-86a7-e42764b272b8">
<br>
- Click “Download” to start the download process.

### Step 3: Install Docker Desktop on Your Mac
After downloading Docker Desktop, you’ll find a .dmg file in your Downloads folder. Here’s what to do next:

- Open the .dmg file by double-clicking on it.
- You’ll see the Docker icon along with an Applications folder. Drag and drop the Docker icon into the Applications folder to begin the installation.
- Once the copy process is complete, Docker is installed on your Mac. You can find it in the Applications folder.

### Step 4: Run Docker Desktop
Open Docker Desktop from your Applications folder. The first time you run Docker, you might see a security warning asking if you really want to open it. Click “Open” to proceed.  

Docker will ask for your password. This is the password you use to log in to your Mac. Docker needs these privileges to run correctly.  

After entering your password, you’ll see the Docker icon appear in your menu bar, indicating Docker is running.  

### Step 5: Increase the Default Resources (Optional)
Docker works fine with its default settings, but depending on what you’re planning to do, you might want to allocate more resources (like memory and CPU) to Docker:

- Click on the Docker icon in the menu bar.
- Select “Preferences.”
- Go to the “Resources” tab where you can adjust the CPUs and memory allocated to Docker.
- After making your adjustments, click “Apply & Restart” for the changes to take effect.

### Step 6: Verify the Installation
To ensure Docker was installed correctly, you can run a simple test by opening Terminal and running a Docker command:

- Open **Terminal** on your Mac.
- Type docker run _hello-world_ and press Enter.
- If Docker is installed correctly, you’ll see a message indicating that your installation appears to be working correctly.

### Step 7: Explore Docker
Congratulations! You’ve successfully installed Docker on your Mac. Now, you’re ready to explore the world of Docker containers. Start by running containers from images available on Docker Hub, creating your own images, or even composing entire applications using Docker Compose




