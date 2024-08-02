# nextjs-setup-no-src
easy nextjs setup for windows (no src)
# ----------------------------------------------------
# Change to the project directory
Set-Location -Path "ADD PATH TO PROJECT"

# Define the directories to be created
$directories = @(
    "components",
    "styles",
    "utils"
)

## -----------------------------------------------

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
