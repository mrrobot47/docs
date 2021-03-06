# ee site reload --type=html

Reload services in containers without restarting container(s) associated with site.

When no service(--nginx etc.) is specified, all services will be reloaded.

[&lt;site-name&gt;]
: Name of the site.

[\--all]
: Reload all services of site(which are supported).

[\--nginx]
: Reload nginx service in container.

### EXAMPLES

    # Reload all containers of site
    $ ee site reload example.com


# ee site reload --type=php

Reload services in containers without restarting container(s) associated with site.

When no service(--nginx etc.) is specified, all services will be reloaded.

[&lt;site-name&gt;]
: Name of the site.

[\--all]
: Reload all services of site(which are supported).

[\--nginx]
: Reload nginx service in container.

[\--php]
: Reload php container of site.

### EXAMPLES

    # Reload all containers of site
    $ ee site reload example.com

    # Reload single containers of site
    $ ee site reload example.com --nginx


# ee site reload --type=wp

Reload services in containers without restarting container(s) associated with site.

When no service(--nginx etc.) is specified, all services will be reloaded.

[&lt;site-name&gt;]
: Name of the site.

[\--all]
: Reload all services of site(which are supported).

[\--nginx]
: Reload nginx service in container.

[\--php]
: Reload php container of site.

### EXAMPLES

    # Reload all containers of site
    $ ee site reload example.com

    # Reload single containers of site
    $ ee site reload example.com --nginx

### GLOBAL PARAMETERS

| **Argument**    | **Description**              |
|:----------------|:-----------------------------|
| `--sites_path=<path>` | Absolute path to where all sites will be stored. |
| `--locale=<locale>` | Locale for WordPress. |
| `--le-mail=<le-mail>` | Mail-id to be used for letsencrypt. |
| `--[no-]color` | Whether to colorize the output. |
| `--debug[=<group>]` | Show all PHP errors; add verbosity to EE bootstrap. |
| `--prompt[=<assoc>]` | Prompt the user to enter values for all command arguments, or a subset specified as comma-separated values. |
| `--quiet` | Suppress informational messages. |
