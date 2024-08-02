# nextjs-setup-no-src
easy nextjs setup for windows (no src)




# Change to the project directory
Set-Location -Path "ADD PATH TO PROJECT"

# Define the directories to be created
$directories = @(
    "components",
    "styles",
    "utils"
)

# Create the directories inside the 'app' directory
foreach ($dir in $directories) {
    New-Item -ItemType Directory -Path ".\app\$dir" -Force
}

# Define the files to be created
$files = @(
    ".\app\components\ChatBox.tsx",
    ".\app\components\ChatMessage.tsx",
    ".\app\components\Login.tsx",
    ".\app\components\UserList.tsx",
    ".\app\pages\_app.tsx",
    ".\app\pages\index.tsx",
    ".\app\pages\chat.tsx",
    ".\app\styles\globals.scss",
    ".\app\styles\ChatBox.module.scss",
    ".\app\styles\ChatMessage.module.scss",
    ".\app\styles\Login.module.scss",
    ".\app\styles\UserList.module.scss",
    ".\app\utils\firebase.ts"
)

# Create the files
foreach ($file in $files) {
    New-Item -ItemType File -Path $file -Force
}

Write-Output "Project structure created successfully."
