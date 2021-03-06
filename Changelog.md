0.3.1
-----
* Added audited apps to acmetool template.

0.3.0
-----
* Fix typo in OAuth2_proxy install path.
* Update to latest AuthGateway version.

0.2.1
-----
* Fix `diff` detection in AcmeTool hook.
* Fix nginx workdir permission to support non-root.

0.2.0
-----
* AuthGateway runs as non-root by default.

0.1.7
-----
* Fix service handler `when` condition.
* Upgrade default version to 0.2.8.

0.1.6
-----
* Customise the `base_dir` configuration option.
* Fix multiline syntax error in acmetool target.
* Optional: create nginx working directory in `base_dir`.
* Optional: render systemd service acmetool hook.
* Update readme.

0.1.5
-----
* Add session cookie name to template variables.
* Document added variables.
* Update templates path to follow ansible convention.

0.1.4
-----
* Can't use `npm run` because `package.json` is not there.
* Systemd needs an absolute path for ExecStart.

0.1.3
-----
* Wrong parameter name for service.

0.1.2
-----
* Better names for tasks.
* More restricted mode for files with sensitive data.

0.1.1
-----
* Fix archive name from GitHub.

0.1.0
-----
* Initial release
