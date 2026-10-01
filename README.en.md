# CognifyAI

[Introduction website](https://cccwww456.github.io/CognifyAI-2.0/%E4%BB%8B%E7%BB%8D%E7%BD%91%E7%AB%99/) · [Product website](https://cccwww456.github.io/CognifyAI-2.0/%E4%BA%A7%E5%93%81%E7%BD%91%E7%AB%99/) · [中文](README.md)

I built CognifyAI to help people get better at working with AI: explaining what they need, working through a task, and deciding what to keep or improve in the result.

## Two ways to start

The **introduction website** explains the project. The **product website** takes you straight into the experience. The introduction's “开始对话” button also opens the product.

These links work after GitHub Pages has finished publishing. Uploading the files alone does not activate the website.

## Using it

CognifyAI brings together conversations, controllable memory, a task canvas, and guided projects. Design, development, and research are the main use cases I am exploring, but the project is not limited to those fields.

Start with demo mode to learn the workflow. It uses prepared examples rather than generating arbitrary content. For real AI responses, enter your own endpoint, model name, and API key in API settings. Image and video services need their own configuration. Availability and charges depend on your provider.

The “登录” button currently opens the product; there is no account login or cloud sync. Records stay in the current browser, so export or back up anything important. Changing devices, clearing browser data, or moving from a local URL to the published site does not automatically transfer your records.

## Testing and progress

The project has already been tried by real people in internal testing, and their feedback has informed changes. It has not only been tested with simulated services.


See [Plans](ROADMAP.md), [Testing and feedback](TESTING.md), and [Publishing instructions](DEPLOYMENT.md).

## Open the downloaded files

Open the root index.html for the introduction, or 产品网站/index.html for the product. If direct file access causes browser restrictions, run `python -m http.server 8000` in the extracted directory and open http://localhost:8000/ . No project dependencies or build step are needed.

The guides are bilingual; the website UI is mainly Chinese. Never upload API keys or private conversation exports. No open-source license is included at this stage.
