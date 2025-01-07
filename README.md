# Completed tutorial on [Frappe Framework](https://docs.frappe.io/framework/user/en/introduction)

You can use commands from the tutorial in the useful_commands.txt

### Library Managment

:Library Management System

### Installation

[Install Frappe Framework](https://docs.frappe.io/framework/v14/user/en/installation) and all necessary dependencies

Then you can install this app using the [bench](https://github.com/frappe/bench) CLI:

```bash
cd $PATH_TO_YOUR_BENCH
bench get-app $URL_OF_THIS_REPO --branch develop
bench install-app library_managment
```

### Contributing

This app uses `pre-commit` for code formatting and linting. Please [install pre-commit](https://pre-commit.com/#installation) and enable it for this repository:

```bash
cd apps/library_managment
pre-commit install
```

Pre-commit is configured to use the following tools for checking and formatting your code:

- ruff
- eslint
- prettier
- pyupgrade

### License

mit
