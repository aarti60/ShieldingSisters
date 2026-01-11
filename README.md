first dowlnoad this zip,
then extract files from zip,
open visual studios,
click on file,
click on open folder them select extracted files ,
now again click on file in vs code then click on new window,
a new window will be opened,
click on new file ,
give your desired name ,
copy all files from old window and paste it in folder of new window,
now select index.html from copied file
then click on f5,

## Run locally (recommended)

If you want to run the project locally from a terminal, here are quick, repeatable steps.

Requirements: Python 3 installed (for a simple static server).

PowerShell (recommended)
```powershell
# from the project root
cd "c:\Users\satav\Downloads\women-safety-project-main"

# start a local static server on port 8000
python -m http.server 8000

# open the site in your default browser
Start-Process "http://localhost:8000"

# stop the server: press Ctrl+C in the terminal where the server is running
```

Windows (find a running background server)
```powershell
Get-Process -Name python
# then stop by PID
Stop-Process -Id <PID>
```

If you prefer a GUI approach, open `index.html` in a browser from your file manager — but some features (like redirects handled via URLs) are more reliable when served over HTTP.

![image](https://github.com/user-attachments/assets/26b711c6-09f7-409d-a2af-1e2c6bd97642)
![image](https://github.com/user-attachments/assets/78b2c6e1-d1e7-4b1a-9b0e-408ad895635f)
![image](https://github.com/user-attachments/assets/c70c354d-ab3e-4939-b9f4-a6ef8ef32d8b)
![image](https://github.com/user-attachments/assets/855d4f74-9c1e-4e69-95ff-4b3b271e1d1f)
![image](https://github.com/user-attachments/assets/7a1f868b-1e97-4cca-8311-79b813c98c74)
![image](https://github.com/user-attachments/assets/b86a9304-aeb1-484f-a3ea-8b1be14711eb)

