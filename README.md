# fireflies_downloader
Bulk download fireflies transcripts using API key

# Create directory 
mkdir fireflies_downloader 
cd fireflies_downloader
 
# Create the Python script 
cursor fireflies_downloader.py 

# Get your API key from Fireflies.ai: 
# 1. Log into Fireflies.ai 
# 2. Go to Settings → Developer Settings → API 
# 3. Copy your API key 
# Set your API key in Terminal 
export FIREFLIES_API_KEY="your_api_key_here"
 
# Install required Python package 
pip3 install requests

# Navigate to the directory (if you're not already there) 
cd fireflies_downloader 

# Run the script 
python3 fireflies_downloader.py
