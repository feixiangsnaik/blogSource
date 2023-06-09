---
title: vscodeConfig
date: 2022-03-29 14:26:37
tags:
---


{
  "workbench.colorTheme": "Community Material Theme",
  "vetur.validation.script": false,
  "vetur.validation.template": false,
  "vetur.validation.style": false,
  "editor.minimap.enabled": false,
  "eslint.enable": true,
  "eslint.autoFixOnSave": true,
  "files.associations": {
    "*.vue": "vue"
  },
  "eslint.options": {
    "extensions": [
      ".js",
      ".vue"
    ]
  },
  "eslint.validate": [
    "javascript",
    {
      "language": "vue",
      "autoFix": true
    },
    "html",
    "vue"
  ],
  "git.ignoreMissingGitWarning": true,
  "editor.detectIndentation": false,
  "editor.tabSize": 2,
  "editor.fontSize": 14,
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true
  },
  "editor.fontLigatures": null,
  "extensions.ignoreRecommendations": true,
  "git.ignoreLegacyWarning": true,
  "update.mode": "none",
  "[vue]": {
    "editor.defaultFormatter": "octref.vetur"
  },
  "[json]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "explorer.confirmDelete": false,
  "[markdown]": {
    "editor.defaultFormatter": "yzhang.markdown-all-in-one"
  },
  "diffEditor.ignoreTrimWhitespace": false,
  "editor.lineNumbers": "on",
  "leek-fund.stocks": [
    "sh000001",
    "sh000300",
    "sh000016",
    "sh000688",
    "hk03690",
    "hk00700",
    "usr_ixic",
    "usr_dji",
    "usr_inx",
    "ZC0",
    "sz000799",
    "sh601012",
    "sh600559",
    "sh603499",
    "sh601099",
    "sz002123",
    "sh512690"
  ],
  "leek-fund.funds": [
    [
      "002258",
      "001532",
      "002943",
      "001644",
      "180012",
      "000297"
    ]
  ],
  "[html]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
}



vscode
1.ssh-keygen -t rsa -b 4096 -f
2.将本地的～/.ssh/id_rsa.pub内容拷贝到服务器下面的~/.ssh/authorized_keys(如果没有.ssh就mkdir创建一个,再创建一个authorized_keys文件）
如果遇到问题，报远程连接错误，那么去known_hosts删除这个ip的一行，然后重新执行上一步