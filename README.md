Personal website

To run locally:
<ol>
    <li>install node.js
        <ul>
            <li>linux: <a href="https://github.com/nvm-sh/nvm">https://github.com/nvm-sh/nvm</a></li>
            <li>windows: <a href="https://github.com/coreybutler/nvm-windows">https://github.com/coreybutler/nvm-windows</a></li>
        </ul>
    </li>
    <li>install npm
        <ol>
            <li>nvm install latest</li>
            <li>nvm use latest</li>
            <li>Set-ExecutionPolicy -ExecutionPolicy Unrestricted -Scope CurrentUser</li>
        </ol>
    </li>
    <li>install cors-anywhere</li>
    <ul>
        <li>npm install cors-anywhere --save</li>
    </ul>
    <li>run local server</li>
    <ul>
        <li>mac: [in achiria.github.io/..] npx http-server -o -p 9999</li>
        <li>windows: npx http-server .\achiria.github.io\ -o -p 9999</li>
    </ul>
</ol> 
