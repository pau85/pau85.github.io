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
    justify-content: center; 
    align-items: center; 
}

    .skill img {
        /*To Do*/
        /*Resize images in GIMP to be 100px x 100 px*/

        width: 100px;
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
    background-color: #282828 !important; 
    color: white; 
}

h1 {
    text-align: center; 
    font-size: 2.5em; 
    margin-top: 20px; 
    padding: 25px;
}
</style>

<!-- Development Experience -->
<h1>My Skillset</h1>
<center>
<table>
    <tbody>
        <tr>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/react-100x100.png" alt="React">
                    <div class="tooltip">React</div>
                </div>
            </td>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/redux.jfif" alt="Redux">
                    <div class="tooltip">Redux</div>
                </div>
            </td>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/typescript.png" alt="TypeScript">
                    <div class="tooltip">TypeScript</div>
                </div>
            </td>
        </tr>
        <tr>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/nodejs.jfif" alt="NodeJs">
                    <div class="tooltip">NodeJS</div>
                </div>
            </td>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/html.jfif" alt="HTML">
                    <div class="tooltip">HTML</div>
                </div>
            </td>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/javascript.png" alt="JavaScript">
                    <div class="tooltip">JavaScript</div>
                </div>
            </td>
        </tr>
        <tr>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/markdown.jfif" alt="Markdown">
                    <div class="tooltip">Markdown</div>
                </div>
            </td>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/restful-api.jfif" alt="restful-api">
                    <div class="tooltip">Restful-API</div>
                </div>
            </td>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/docker.png" alt="docker">
                    <div class="tooltip">Docker</div>
                </div>
            </td>
        </tr>
        <tr>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/java.png" alt="java">
                    <div class="tooltip">Java</div>
                </div>
            </td>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/csharp.jfif" alt="csharp">
                    <div class="tooltip">C#</div>
                </div>
            </td>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/python.jfif" alt="python">
                    <div class="tooltip">Python</div>
                </div>
            </td>
        </tr>
        <tr>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/ibm-mainframe.jfif" alt="mainframe">
                    <div class="tooltip">Mainframe</div>
                </div>
            </td>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/jcl-mainframe.jfif" alt="jcl">
                    <div class="tooltip">JCL</div>
                </div>
            </td>
            <td>
                <div class="skill">
                    <img src="/assets/img/skills/pl1-ibm-mainframe.jfif" alt="PL1">
                    <div class="tooltip">PL1</div>
                </div>
            </td>
        </tr>
        <!-- Add more rows as needed -->
    </tbody>
</table>
</center>
