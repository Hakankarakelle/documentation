{
  "home_assistant": {
    "installation_type": "Home Assistant OS",
    "version": "2023.10.5",
    "dev": false,
    "hassio": true,
    "virtualenv": false,
    "python_version": "3.11.5",
    "docker": true,
    "arch": "x86_64",
    "timezone": "Europe/Istanbul",
    "os_name": "Linux",
    "os_version": "6.1.59",
    "supervisor": "2023.10.1",
    "host_os": "Home Assistant OS 11.1",
    "docker_version": "24.0.6",
    "chassis": "vm",
    "run_as_root": true
  },
  "custom_components": {
    "hacs": {
      "version": "1.33.0",
      "requirements": [
        "aiogithubapi>=22.10.1"
      ]
    }
  },
  "integration_manifest": {
    "domain": "hacs",
    "name": "HACS",
    "codeowners": [
      "@ludeeus"
    ],
    "config_flow": true,
    "dependencies": [
      "http",
      "websocket_api",
      "frontend",
      "persistent_notification",
      "lovelace",
      "repairs"
    ],
    "documentation": "https://hacs.xyz/docs/configuration/start",
    "iot_class": "cloud_polling",
    "issue_tracker": "https://github.com/hacs/integration/issues",
    "requirements": [
      "aiogithubapi>=22.10.1"
    ],
    "version": "1.33.0",
    "is_built_in": false
  },
  "data": {
    "entry": {
      "entry_id": "e552b152623e7caeb17823f5d81eb666",
      "version": 1,
      "domain": "hacs",
      "title": "",
      "data": {
        "token": "**REDACTED**"
      },
      "options": {
        "sidepanel_title": "HACS",
        "sidepanel_icon": "hacs:hacs",
        "release_limit": 5,
        "country": "ALL",
        "appdaemon": true,
        "netdaemon": true,
        "debug": true,
        "experimental": false
      },
      "pref_disable_new_entities": false,
      "pref_disable_polling": false,
      "source": "user",
      "unique_id": null,
      "disabled_by": null
    },
    "hacs": {
      "stage": "running",
      "version": "1.33.0",
      "disabled_reason": "rate_limit",
      "new": false,
      "startup": false,
      "categories": [
        "integration",
        "plugin",
        "theme",
        "appdaemon"
      ],
      "renamed_repositories": {},
      "archived_repositories": [],
      "ignored_repositories": [],
      "lovelace_mode": "storage",
      "configuration": {
        "appdaemon": true,
        "country": "ALL",
        "debug": true,
        "dev": false,
        "experimental": false,
        "netdaemon": true,
        "python_script": false,
        "release_limit": 5,
        "theme": false
      }
    },
    "custom_repositories": [],
    "repositories": [
      {
        "data": {
          "archived": false,
          "authors": [
            "@ludeeus"
          ],
          "category": "integration",
          "config_flow": true,
          "default_branch": "main",
          "description": "HACS gives you a powerful UI to handle downloads of all your custom needs.",
          "domain": "hacs",
          "downloads": 149538,
          "etag_repository": "W/\"6ba4761d484220d1df4502377793b3a5c51c1d60be41a17f9169b36d6d5efa35\"",
          "etag_releases": null,
          "file_name": "",
          "first_install": false,
          "full_name": "hacs/integration",
          "hide": false,
          "has_issues": true,
          "id": "172733314",
          "installed_commit": null,
          "installed_version": "1.33.0",
          "installed": true,
          "last_commit": "ad64bc7",
          "last_updated": "2023-10-26T18:29:46Z",
          "last_version": "1.33.0",
          "manifest_name": "HACS",
          "new": false,
          "open_issues": 5,
          "published_tags": [
            "1.33.0",
            "1.32.1",
            "1.32.0",
            "1.31.0",
            "1.30.1"
          ],
          "releases": true,
          "selected_tag": null,
          "show_beta": false,
          "stargazers_count": 3986,
          "topics": [
            "community",
            "package-manager"
          ]
        },
        "integration_manifest": {
          "domain": "hacs",
          "name": "HACS",
          "codeowners": [
            "@ludeeus"
          ],
          "config_flow": true,
          "dependencies": [
            "http",
            "websocket_api",
            "frontend",
            "persistent_notification",
            "lovelace",
            "repairs"
          ],
          "documentation": "https://hacs.xyz/docs/configuration/start",
          "iot_class": "cloud_polling",
          "issue_tracker": "https://github.com/hacs/integration/issues",
          "requirements": [
            "aiogithubapi>=22.10.1"
          ],
          "version": "0.0.0"
        },
        "repository_manifest": {
          "content_in_root": false,
          "country": [],
          "filename": "hacs.zip",
          "hacs": "0.19.0",
          "hide_default_branch": true,
          "homeassistant": "2023.6.0",
          "manifest": {
            "name": "HACS",
            "zip_release": true,
            "hide_default_branch": true,
            "homeassistant": "2023.6.0",
            "hacs": "0.19.0",
            "filename": "hacs.zip"
          },
          "name": "HACS",
          "persistent_directory": null,
          "render_readme": false,
          "zip_release": true
        },
        "ref": "1.33.0",
        "paths": {
          "localpath": "/config/custom_components/hacs",
          "local": "/config/custom_components/hacs",
          "remote": "custom_components/hacs"
        }
      }
    ],
    "rate_limit": {
      "resources": {
        "core": {
          "limit": 5000,
          "used": 3995,
          "remaining": 1005,
          "reset": 1698491714
        },
        "search": {
          "limit": 30,
          "used": 0,
          "remaining": 30,
          "reset": 1698489948
        },
        "graphql": {
          "limit": 5000,
          "used": 0,
          "remaining": 5000,
          "reset": 1698493488
        },
        "integration_manifest": {
          "limit": 5000,
          "used": 0,
          "remaining": 5000,
          "reset": 1698493488
        },
        "source_import": {
          "limit": 100,
          "used": 0,
          "remaining": 100,
          "reset": 1698489948
        },
        "code_scanning_upload": {
          "limit": 1000,
          "used": 0,
          "remaining": 1000,
          "reset": 1698493488
        },
        "actions_runner_registration": {
          "limit": 10000,
          "used": 0,
          "remaining": 10000,
          "reset": 1698493488
        },
        "scim": {
          "limit": 15000,
          "used": 0,
          "remaining": 15000,
          "reset": 1698493488
        }
      },
      "rate": {
        "limit": 5000,
        "used": 3995,
        "remaining": 1005,
        "reset": 1698491714
      }
    }
  }
}---
id: diagnostics
title: Diagnostics
description: 'How to get HACS diagnostics'
---

The diagnostics dump is a JSON file with information about your instance, this is useful to upload to GitHub when creating issues.
To get the diagnostics dump for HACS do the following:

1. First go to the "Settings" in the Home Assistant UI, then "Devices & Services" and the "Integrations" tab in the Home Assistant UI
1. Then click on the entry for HACS.
1. Then click on the 3 dots to the right of the card for HACS, and select "Download diagnostics"

![image showing how to download diagnostics](/img/diagnostics.png)

This will download a file with `json.txt` file ending to the computer you are doing this from (usually the downloads directory), this file can be pasted or dragged into GitHub issues.
