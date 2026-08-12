  Here are the exact 3 simple steps to activate CYD AGYDeck Pro when you unbox a brand-new CYD board:              
  
  ──────
  ### 1. Plug In Your New CYD Board
  
  Connect your new CYD board to your computer using a USB cable.
  
  ──────
  ### 2. Flash the Board (One Command)
  
  Open a terminal and run the one-click flashing script from your repository:
  
   cd /home/ssdjmjro/CYD-AGYDeck-Pro
    ./scripts/flash.sh
  
  (If you are on a new computer, just clone your repo first with git clone https://github.com/ssdjmjro/CYD-AGYDeck-
  Pro.git)
  
  Your new CYD screen will immediately light up with the CYD AGYDeck Pro v6.0 Cyberpunk UI! 📺
  
  ──────
  ### 3. Run the PC Companion Daemon
  
  In your terminal, start the companion script so your PC feeds live stats to CYD and responds to touch buttons    
  (TabForge Studio, AGY AI Agent, Terminal, Music Control):
  
   cd /home/ssdjmjro/CYD-AGYDeck-Pro
    ./scripts/run_companion.sh
   
  ──────
  ### 💡 Alternative: MicroSD Card Method (No Terminal Needed)
  
  If your new CYD board has ESP32 Firmware Launcher:
  
  1. Copy CYD_StreamDeck_SD.bin to a FAT32 MicroSD card.
  2. Insert the card into your new CYD.
  3. Turn on the board -> Select CYD_StreamDeck_SD.bin -> Tap Install/Run.
