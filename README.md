# Andrea Gallegati

Hi there! I'm an aerospace engineer, and I love programming — that’s why I decided to write my CV in LaTeX! Another reason is that, with a PhD under my belt, I know LaTeX well and genuinely appreciate its precision and flexibility. I’m also passionate about automation, deployment, and containerization, which led me to set up this project in a `devcontainer`. My CV is automatically built with every push/merge into the master branch and deployed as a GitHub page.

You can download both versions of my CV below:

- [Extended Version](https://andreagalle.github.io/cv/long.pdf) (Detailed CV)
- [One-Pager](https://andreagalle.github.io/cv/short.pdf) (Short Version)

## Cloning This Project
To clone this repository, ensuring the `.devcontainer` submodule is fetched automatically, run the following commands and follow the instructions you can find there:

    git clone --recurse-submodules https://github.com/andreagalle/cv.git

then, to fetch the latest commit from the submodule repository:

    git submodule update

to list all submodules and their status:

    git submodule

If you have already cloned this repository, you can still initialize and update the `LaTeX` submodule with:

    git submodule update --init --recursive

I hope you enjoy reading my CV project. Happy coding!
