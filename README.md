### Synte Edu Mobile App Tech

#Parents/Gurdian Mobile App for Frappe Education

Features:
Frappe has Education App but it lacks Mobile App for Parents/Gurdian so this mobile App is close the gap
Easy Parent Details, Frappe app has Gurdian Linking to Student which need several step, this app add few property to Student DocType which makes lot easier to fill parent details (by import or manaul entry)

### Installation

You can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch develop
bench install-app synte_edu_tech
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

```bash
cd apps/synte_edu_tech
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### CI

This app can use GitHub Actions for CI. The following workflows are configured:

- CI: Installs this app and runs unit tests on every push to `develop` branch.
- Linters: Runs [Frappe Semgrep Rules](https://github.com/frappe/semgrep-rules) and [pip-audit](https://pypi.org/project/pip-audit/) on every pull request.


### License

mit

# synte_edu_tech
Parents/Gurdian Mobile App for Frappe Education
>>>>>>> origin/main
