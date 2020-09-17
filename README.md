# Jina X Hackathon Support Repo

This repo has been put together by Jina for support during the Jina X Hackathon in September 2020.

**Note**: This repo is **not** a place for teams to host their projects. Teams should do that on their own repo!

## You need to know this!!!

* Use [Jina 0.5.5](https://pypi.org/project/jina/0.5.5/)
* Use Python 3.7 or 3.8
* On Windows? Use [Virtualbox](https://www.virtualbox.org/) and install [Ubuntu 20.04](https://releases.ubuntu.com/20.04/) to use Jina. [[How do I install Ubuntu on Virtualbox?](https://www.youtube.com/watch?v=x5MhydijWmc)]
* Use a [virtual environment](https://pythonbasics.org/virtualenv/) when developing anything in Python to avoid library conflicts.

* [FAQ](./FAQ.md)
* Got a question? [Put it here](./questions.md) or ask in the Slack group

## Learn About Jina

| What                 | Where                                                                                  |
| ---                  | ---                                                                                    |
| Intro video          | [YouTube link](https://www.youtube.com/watch?v=Fe6K3zjujlQ)                            |
| Overview             | Check our [README](https://github.com/jina-ai/jina/)                                   |
| Core concepts        | [Jina 101](https://github.com/jina-ai/jina/tree/master/docs/chapters/101)              |
| Build your first app | [My First Jina App](https://github.com/jina-ai/examples/tree/master/my-first-jina-app) |
| More examples        | https://github.com/jina-ai/examples                                                    |

## Facing Issues?

| What      | Where                              |
| ---       | ---                                |
| Bugs      | Post an issue in our relevant repo |
| Questions | Post on #mentors_desk in Slack     |

## Key Features in a Project

Your project must have these to be considered for judgement:

### `requirements.txt`

All projects **must** have a `requirements.txt` that lists `jina` (all lower case), preferably with the version you are using (e.g. `jina==0.5.5`). 

If you're in a virtual environment, you can do this automatically (for Jina and all your other dependencies) by running `pip freeze > requirements.txt` [[More info here](https://pip.pypa.io/en/stable/reference/pip_freeze/)]

## Troubleshooting

* Are you having trouble querying through Jinabox? Try a query through `curl` instead (this is usually explained in an example's `README.md`). `curl` is a very old, very mature piece of software - if `curl` fails it's likely a Jina configuration problem (or a Jina bug!). Be sure to check the hostname and ports too!

## Contribute to Jina

Please see our [Contributor Guide](https://github.com/jina-ai/jina/blob/master/CONTRIBUTING.md)
