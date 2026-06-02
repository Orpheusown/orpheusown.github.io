# orpheusown.github.io

Personal academic homepage of **Yu Wang**, Ph.D. student in Intelligent Systems Engineering at Indiana University Bloomington.

Live at **[orpheusown.github.io](https://orpheusown.github.io/)**.

## Structure

```
.
├── index.html      # main page (bio, research, publications)
├── style.css       # styles
├── images/         # profile photo
├── files/          # CV PDF
└── README.md
```

## Local preview

It's a static site — open `index.html` directly, or run any static server:

```sh
python3 -m http.server 4000
# then visit http://localhost:4000
```

## Updating

- **Bio / sections** — edit `index.html`.
- **New publication** — add an `<li>` to the appropriate year block under `<section id="publications">` in `index.html`.
- **CV** — drop a new `CV_YuWang.pdf` into `files/`.
- **Photo** — replace `images/yu-wang.jpg`.

## License

Content © Yu Wang. Code released under the MIT License (see `LICENSE`).
