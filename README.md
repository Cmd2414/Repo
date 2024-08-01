# installa SocialFish


1. **Install Termux**:
   - If you don't have Termux installed yet, get it from [F-Droid](https://f-droid.org/packages/com.termux/) or the Google Play Store.

2. **Open Termux**:
   - Launch Termux after installation.

3. **Update Packages**:
   - Run the following commands to ensure your packages are up to date:
     ```
     -> pkg update
     -> pkg upgrade
     ```

4. **Install Git and Python**:
   - SocialFish requires Python and Git. Install them with:
     ```
     -> pkg install git
     -> pkg install python
     ```

5. **Clone the SocialFish Repository**:
   - Use Git to clone the SocialFish repository from GitHub:
     ```
    ->  git clone https://github.com/UndeadSec/SocialFish.git
     ```

6. **Navigate to the SocialFish Directory**:
   - Change to the SocialFish directory:
     ```
     -> cd SocialFish
     ```

7. **Install Python Dependencies**:
   - SocialFish requires certain Python libraries. Install them with:
     ```
     -> pip install -r requirements.txt
     ```

8. **Run SocialFish**:
   - Start SocialFish with:
     ```
     -> python SocialFish.py
     ```

9. **Additional Configuration**:
   - When you run SocialFish, it will prompt you for some initial configuration. Follow the on-screen instructions to complete the setup.

