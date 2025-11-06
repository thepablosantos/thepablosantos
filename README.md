Hi, I'm Pablo Santos ✌️

```solidity
// SPDX-License-Identifier: MIT
pragma solidity ^0.8.18;

contract GitHubProfile {
    string public welcomeMessage;

    event Deployed(address indexed by);
    event Greeted(string message);

    constructor() {
        welcomeMessage = "Hello! Welcome to my GitHub profile!";
        emit Deployed(msg.sender);
    }

    function greet() public returns (string memory) {
        emit Greeted(welcomeMessage);
        return welcomeMessage;
    }
}

```

[![Linkedin Badge](https://img.shields.io/badge/-Linkedin-007acc?style=flat-square&logo=LinkedIn&logoColor=white&link=https://www.linkedin.com/in/pablo-sodre/)](https://www.linkedin.com/in/pablo-sodre/)
[![Portfolio](https://img.shields.io/badge/Portfolio-pablosantos.xyz-0A66C2?style=for-the-badge&logo=vercel)](https://www.pablosantos.xyz)


[//]: # (<a href="https://github.com/thepablosantos">)
[//]: # (    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=alvinscheibe&show_icons=true&theme=github_dark&include_all_commits=true&count_private=true&hide=contribs,issues" />)
[//]: # (</a>)

<div style="display: inline_block"><br />
    <img alt="Solidity" height="30" width="40" src="https://upload.wikimedia.org/wikipedia/commons/9/98/Solidity_logo.svg">
    <img alt="NodeJS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/nodejs/nodejs-original.svg">
    <img alt="TypeScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-plain.svg">
    <img alt="Docker" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/docker/docker-original.svg">
    <img alt="React" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg">
    <img alt="JavaScript" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/javascript/javascript-original.svg">
    <img alt="CSS" height="30" width="40" src="https://raw.githubusercontent.com/devicons/devicon/master/icons/css3/css3-original.svg">
</div>
