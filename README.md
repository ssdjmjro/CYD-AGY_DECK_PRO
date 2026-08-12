 ### 1 Step 1: Download Your Repo / ZIP
  
  On your new computer, open a terminal and clone your GitHub repository:
  
  git clone https://github.com/ssdjmjro/CYD-AGYDeck-Pro.git
  cd CYD-AGYDeck-Pro
  
  (Or transfer and unzip your CYD_AGYDeck_Pro_v7.0.zip file, then cd CYD-AGYDeck-Pro)

  ──────
  ### 2 Step 2: Flash Your CYD Board (1 Command)
  
  Plug your CYD board into USB and run the auto-flashing script:
  
  ./scripts/flash.sh

  • What it does: Auto-detects your USB port, fixes permissions, installs esptool, and flashes the firmware to your
  board in ~10 seconds!
  
  ──────
  ### 3 Step 3: Run the PC Companion App (1 Command)
  
  In your terminal, run the companion script:
  
  ./scripts/run_companion.sh
  
  • What it does: Auto-installs Python dependencies (pyserial, psutil), connects to your CYD board over USB, feeds 
  live PC CPU/RAM/Network stats, and enables touch control for TabForge Studio, AGY AI, Terminal, Google, Files,   
  and Music!
