Shell script to update your Slack app theme to dark mode


You'll need the `asar` NPM module to unpack the slack files to modifiy:

```
npm install -g asar
```

Usage:

```
> git clone https://github.com/m-martinez/slack-darkmode.git
> cd slack-darkmode
> sudo ./slack-darkmode
```

You need to run the shell script in sudo to modify your installed Slack application.

## Troubleshooting

### Slack reverted to old theme

This means that you Slack app auto-updated. Run the script again.

## Acknowledgments

* This project uses CSS that is a modified fork of: https://github.com/laCour/slack-night-mode
* https://qiita.com/shoken/items/4f0bbba9b5d911657b5a
