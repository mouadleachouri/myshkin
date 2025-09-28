# Branch nomenclature

The branch name must strictly follow the following format for a PR to be accepted:

```
<initials>-<feature>
```

So, if your name is Gregor Samsa, and you're making a bash script called
`export.sh` into a POSIX-compliant shell script, the branch name should look
something like:

```
gs-remove-bashisms-exportsh
```

# Commit message

The commit message must follow an Angular-like template:

```
<type>(<scope>): <title>

<body>
```

## Type

`<type>` can be one of the following:

- `feat`: a new feature.
- `fix`: a bug fix.
- `docs`: documentation.
- `refactor`: none of the above.

## Scope

## Title

`<title>` must describe, precisely and consisely, the changes that the commit
introduced to the repository.

- The commit title must not end with a period
- The commit message must describe the changes precisely enough; please avoid
  vague titles like `"update foo.bar"` or `"fix typo"`.

# Linting

We use different linters for different file types:

- `ruff`: for Python.

# File formatting

Every file must be correctly formatted before being pushed to the repository.

Some general guidelines must be followed:

- A maximum line width of 80 characters (if you're using vim, which you
  _should_, use `gq` on a visual line to break it).
- No traling white spaces.

We use different formatters for different file types.

- `prettier`: for every file type that it supports, including Markdown and
  HTML.
- `ruff`: for Python files.
