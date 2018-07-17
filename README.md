## Welcome to KIP-Tools

This site exposes information related to a family of tools devoted to facilitate handling the **Lifecycle of Knowledge Intensive Processes (KIPs)**. KIPs are known to be complex, goal oriented and knowledge dependent thus making KIPs' lifecycle unpredictable and hard to manage. We plan to reveal the metamodel we use to define our core concepts and how they relate. We also plan to expose the tool architecture and functionalities.

The tools are academic initiatives, typically developed by a MSc. or PhD. student of our research group. 


The site is built on **GitHub Pages** and **Jekyll**, integrated with **Docker** container to facilitate editing.

To create the site locally use:

> 1. make sure you have installed **Docker** and the **Jekyll** container ()
>
> 2. download/clone the **kip-tools** repo
> 3. cd to the local **kip-tools** root
> 4. build the site with the command : docker-compose run jekyll jekyll build
> 5. serve the site with the command : docker-compose run --service-ports jekyll jekyll serve
> 6. check at http://0.0.0.0:4000

Make changes using your local editor and the local site will be update automatically. Check [Jekyll/Docker](https://github.com/envygeeks/jekyll-docker/blob/master/README.md) for more information

To browse the site go to:

> 1. https://toacy.github.io/kip-tools/
