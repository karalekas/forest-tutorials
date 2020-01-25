Interactive tutorial notebooks for pyQuil and Forest
====================================================

[![Binder](https://mybinder.org/badge_logo.svg)][binder]

This is a Binder repository containing tutorial notebooks for learning about [pyQuil][pyquil] and
the Forest SDK ([quilc][quilc] and the [QVM][qvm]). If you'd like to add a notebook, or change an
existing one, make a pull request! And, to run the existing notebooks in a preconfigured environment
on Binder, click the badge above!

Alternatively, you can run the image locally with the following command (replacing `PORT`
with the `localhost` port you'd like to run the notebook server on):

```bash
docker run -p PORT:8888 rigetti/forest-tutorials
```

This will start the container, and somewhere in the terminal output it will print a URL that
looks something like the following, but with `TOKEN` replaced with a long string of letters
and numbers:

```
http://127.0.0.1:8888/?token=TOKEN
```

Copy paste the above URL into your browser, replacing 8888 with `PORT`. This will bring up the
JupyterLab interface.

[arxiv]: https://arxiv.org/abs/2001.04449
[binder]: https://mybinder.org/v2/gh/rigetti/forest-tutorials/master?urlpath=lab/tree/Welcome.ipynb
[pyquil]: https://github.com/rigetti/pyquil
[qvm]: https://github.com/rigetti/qvm
[quilc]: https://github.com/rigetti/quilc
