 
  #### Step 1: Get the Project on Your New Computer
  
  Open a terminal on your new computer and run:
  
   git clone <your-repo-url> CYD-AGYDeck-Pro
   cd CYD-AGYDeck-Pro
  
  ──────
  #### Step 2: Flash the Firmware to Your New CYD Board
  
  1. Connect your new CYD board to your computer using a USB cable.
  2. Run the one-click flashing script:
    chmod +x scripts/flash.sh
    ./scripts/flash.sh
  (Alternative without flashing script: Copy CYD_StreamDeck_SD.bin to a MicroSD card and launch it via ESP32       
  Launcher on the board).
  
  ──────
  #### Step 3: Enable Auto-Connect on the New Computer
  
  Run the auto-connect service installer script:
  
   chmod +x scripts/setup_autoconnect.sh
   ./scripts/setup_autoconnect.sh
   
   ──────
  ### 🎉 You're All Set!
  
  • The companion service is now running in the background on your new PC.
  • From now on, whenever you plug the CYD board into USB, it will automatically connect and start streaming your  
  PC telemetry and launcher controls!

