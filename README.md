# 🎭Artifact #
[![Artifact](https://github.com/zafeirisdimi/artifact/actions/workflows/artifact.yml/badge.svg?branch=main)](https://github.com/zafeirisdimi/artifact/actions/workflows/artifact.yml)
<br/>

## 🏴‍☠️Challenge ##

<ul><h3>Develop a workflow that creates an artifact</h3> 
<li> Workflow file in a new repo </li>
<li> Push trigger </li>
<li> Enivonment variable for the artifact name</li>
<li>One job with two steps
    <ol>
    <li>actions/checkout</li>
    <li>actions-artifact</li>
    </ol>
</li>
</ul>

## 💡Solution ##

<h3>Steps to solve the challenge:</h3>
<ol>
 <li>Create a new repository as artifact</li>
 <li>Add a Readme</li>
 <li>Press Create New Repository</li>
 <li>Create new file, with path .github/workflows/artifact.yml </li>
 <li>See all the details of file artifact.yml</li>
 <li>In the section of steps, we set a name for each step and include the <strong>action/checkout</strong> and <strong>action/upload-artifact</strong>
 <li> For configure the action/upload-artifact, we use the variable <strong>ARTIFACT_NAME</strong> and <strong>path</strong> as with parameters
 <li> Press Commit new changes</li>
 <li> In the section of Actions, we noticed that our workflow start to run successfully</li>
 <li> Well done!!! 😃 </li>
</ol>

## ❓FAQ ##

<h5>What is a workflow artifact for Github Actions?</h5>
<p>
<details>
    <summary><h5>Answer:</h5></summary>
    <p>An artifact is a file or collection of files produced during a workflow run. <br/>For example, you can use artifacts to save your build and test output after a workflow run has ended. <br/>All actions and workflows called within a run have write access to that run's artifacts</p>

</details>
</p>

