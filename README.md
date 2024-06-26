
<a name="readme-top"></a>

<div align="center">
  <h3 align="center">Langchain Training</h3>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#installation">Installation</a></li>
      </ul>
    </li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



### Built With

* ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
* ![Streamlit](https://img.shields.io/badge/streamlit-%23FFFFFF.svg?style=for-the-badge&logo=streamlit&logoColor=FF4B4B)
* Langchain

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started
To get a local copy up and running follow these simple example steps.


### Installation

1. Get API Keys at [https://platform.openai.com/](https://platform.openai.com/) and [https://smith.langchain.com/](https://smith.langchain.com/) as well as a project name at Langsmith.
2. Clone the repo
   ```sh
   git clone https://github.com/asakohayase/langchain_chatbot
   ```
3. Install packages
   ```sh
   pip install -r requirements.txt 
   ```
4. Enter your API keys in `.env`
   ```js
   OPENAI_API_KEY='ENTER YOUR API';
   LANGCHAIN_API_KEY='ENTER YOUR API';
   LANGCHAIN_PROJECT='ENTER YOUR PROJECT NAME';
   ```

### Usage
To use the application, run the .py files with the streamlit CLI (after having installed streamlit):
   ```sh
   streamlit run app.py
   ```
You have to run the Ollama language model in order to use Ollama:
   ```sh
   ollama run llama2
   ```

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* [https://img.shields.io/github/contributors/othneildrew/Best-README-Template.svg?style=for-the-badge](https://www.youtube.com/watch?v=swCPic00c30&t=2779s)


<p align="right">(<a href="#readme-top">back to top</a>)</p>
