Terminal Commands (VS Code PowerShell):


mkdir web-development-practice
cd web-development-practice
mkdir week-1, week-2, week-3
New-Item week-1/index.html
New-Item week-2/index.html
New-Item week-3/index.html
cd week-1
cd ..
Rename-Item week-3 temp
Rename-Item temp week-3
mkdir test
rmdir test
code .

Final Folder Structure:

web-development-practice/
├── week-1/
│   └── index.html
├── week-2/
│   └── index.html
└── week-3/
    └── index.html