# notion-clear-trash

A small script to clear the trash from Notion

### How to Run the Script

1. Clone the repository
```bash
git clone https://github.com/w4v3s/notion-clear-trash.git
```
2. Install requirements
```bash
pip3 install -r requirements.txt
```
3. Run python script
```bash
python3 notion-clear-trash.py
```

### How to Retrieve the Auth Token_v2 (in Chrome)

Go this documentation: https://www.notion.so/Find-Your-Notion-Token-5da17a8df27a4fb290e9e3b5d9ba89c4

1. Go to notion.so
2. Open developer tools (hit F12)
3. Navigate to the Application tab (may be hidden if the developer window is small)
4. Expand Cookies under the Storage section on the sidebar
5. Click on 'https://www.notion.so' to view all the cookies
6. Copy the value for the key 'token_v2'
