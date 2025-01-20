---
layout: page
---

<style>

    .skill-container {
        display: flex;
        flex-wrap: wrap;
    }

    .skill {
    position: relative;
    margin: 10px;
    display: flex;
    justify-content: center; /* Center horizontally */
    align-items: center; /* Center vertically */
}

    .skill img {
        /*To Do*/
        /*Resize images in GIMP to be 100px x 100 px*/

        width: 200px;
        height: 100px; 
        border-radius: 10px;
    }

    .skill .tooltip {
        visibility: hidden;
        width: 120px;
        background-color: black;
        color: #fff;
        text-align: center;
        border-radius: 5px;
        padding: 5px;
        position: absolute;
        z-index: 1;
        bottom: 125%;
        left: 50%;
        margin-left: -60px;
        opacity: 0;
        transition: opacity 0.3s;
    }

    .skill:hover .tooltip {
        visibility: visible;
        opacity: 1;
    }
   
table thead tr, table tbody tr {
    background-color: #282828 !important; /* Set your desired background color */
    color: white; /* Optional: Set text color to white for better contrast */
}

h1 {
    text-align: center; /* Center align the title */
    font-size: 2.5em; /* Adjust the size as needed */
    margin-top: 20px; /* Add some top margin */
    padding: 10px;
}
</style>

<!-- ## Professional Web Development Experience -->
<h1>My Skillset</h1>
<table>
    <thead>
        <tr>
            <th>Front-End Tech</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <div class="skill">
                <img src="/assets/img/skills/react-100x100.png" alt="React">
                <div class="tooltip">React</div>
            </div>
        </tr>
        <tr>
            <div class="skill">
                <img src="/assets/img/skills/typescript.png" alt="TypeScript">
                <div class="tooltip">TypeScript</div>
            </div>
        </tr>
        <tr>
            <div class="skill">
                <img src="/assets/img/skills/html.jfif" alt="HTML">
                <div class="tooltip">HTML</div>
            </div>
        </tr>
        <tr>
                <div class="skill">
                    <img src="/assets/img/skills/javascript.png" alt="JavaScript">
                    <div class="tooltip">JavaScript</div>
                </div>
        </tr>
        <tr>
            <div class="skill">
                <img src="/assets/img/skills/nodejs.jfif" alt="NodeJs">
                <div class="tooltip">NodeJS</div>
            </div>
        </tr>
        <tr>
            <div class="skill">
                <img src="/assets/img/skills/markdown.jfif" alt="Markdown">
                <div class="tooltip">Markdown</div>
            </div>
        </tr>
        <tr>
            <div class="skill">
                <img src="/assets/img/skills/redux.jfif" alt="Redux">
                <div class="tooltip">Redux</div>
            </div>
        </tr>
        <tr>
            <div class="skill">
                <img src="/assets/img/skills/restful-api.jfif" alt="Redux">
                <div class="tooltip">Redux</div>
            </div>
        </tr>
        <!-- Add more rows as needed -->
    </tbody>
</table>
<!-- 
<table>
    <thead>
        <tr>
            <th>Back-End Tech</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <div class="skill">
                <img src="/assets/img/skills/csharp.jfif" alt="C#">
                <div class="tooltip">C#</div>
            </div>
        </tr>
        <tr>
            <div class="skill">
                <img src="/assets/img/skills/ibm-mainframe.jfif" alt="Mainframe">
                <div class="tooltip">Mainframe</div>
            </div>
        </tr>
        <tr>
            <div class="skill">
                <img src="/assets/img/skills/ibm-db2.png" alt="DB2">
                <div class="tooltip">DB2</div>
            </div>
        </tr>
    </tbody>
</table> -->
<!-- Professional Web Development Experience
Tech Stack:
React-Redux
TypeScript and some Javascript
HTML/CSS

Tools
Docker
GitLab
Tmux
iTerm
PowerShell
VSCode

External Systems
Kafka
Kubernetes

Professional Backend Programming Experience

Personal Project Experience -->
