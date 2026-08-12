#### Step 1: Unzip the Package
  
  Copy CYD_AGYDeck_Pro_v7.0.zip to your laptop and extract it:
  
  unzip CYD_AGYDeck_Pro_v7.0.zip
  cd CYD-AGYDeck-Pro
  
  ──────
  #### Step 2: Flash Your CYD Board (1 Command)
  
  Plug your new CYD board into USB and run:
  
  ./scripts/flash.sh
  
  • What it does: Auto-detects your USB serial port (/dev/ttyUSB* / /dev/ttyACM*), fixes permissions, installs     
  esptool, and flashes the firmware to your board in ~10 seconds!

  ──────
  #### Step 3: Start the PC Companion App (1 Command)
  
  Run the companion script in your terminal:
  
  ./scripts/run_companion.sh
  
  • What it does: Connects to your CYD board, streams live CPU/RAM/Network stats, and listens for touch actions on 
  your screen (TabForge Studio, AGY AI Agent, Terminal, Google, Music controls)!

  ──────
  ### 💡 MicroSD Card Option (No Cable Required)
  
  If you want to load it via MicroSD card on an ESP32 Firmware Launcher:
  
  • Copy the file CYD-AGYDeck-Pro/bin/CYD_StreamDeck_SD.bin to a FAT32 MicroSD card.
  • Insert into your CYD board -> Boot up -> Select CYD_StreamDeck_SD.bin -> Tap Install.
