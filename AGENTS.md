## Before you start

Read the `PERSONAILITY.md` to understand who want to create a resume and what he/she want to add to his/her resume.

Collect all the information from the `/references` dir and then follow the `PERSONAILITY.md` to create a resume. The resume should not related to any documents in the `/references` dir, but should be based on the information in the `/references` dir.

## How to use RenderCV to create a Resume

### Install

rendercv has been ready to use in `.venv`, rember to activate the virtual environment before using rendercv or you could also use the interpreter in `.venv` to run rendercv.

### Usage

Create a new CV yaml file:

```sh
rendercv new "John Doe"
```

Edit the YAML, then render:`

```sh
rendercv render "John_Doe_CV.yaml"
```
For more details, see the user guide.

### Workdir

The default workdir is `./output`, edit/render file under this directory.