# Description
Script to add the prefix from tailwind config to all classes of your React project.

# How to install
To use the script you need to install `fs-extra` in your project:
```sh
npm install fs-extra
```

# How to use
Download the script file and run the command below:
```sh
node updatePrefix.js                # to add 
node updatePrefix.js <old-prefix>-  # to replace previous prefix by the new one in tailwind.config.js
```

You are free to download and modify the script as needed for your project.

> If there is no prefix defined in `tailwind.config.js` and you use an old prefix in the previous command, then the script will remove your old prefix.

> In my original project, I used the package "classnames" imported as "cn". That's why you can find "[cn]" in some RegExp expressions.
