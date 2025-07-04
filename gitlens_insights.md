## ash (ash@sorrel.sh) on 2024-12-17: Fix `https` behaviour in fish (#1611)
extras/httpie-completion.fish

## github-actions[bot] (41898282+github-actions[bot]@users.noreply.github.com) on 2024-11-01: [automated] Update generated content (#1607)
extras/man/http.1
extras/man/httpie.1
extras/man/https.1

## Jakub Roztocil (jakub@roztocil.co) on 2024-11-01: 3.2.4
CHANGELOG.md
extras/man/http.1
extras/man/httpie.1
extras/man/https.1
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2024-11-01: Update test.yml
.github/workflows/tests.yml

## Jakub Roztocil (jakub@roztocil.co) on 2024-11-01: Fix/refactor default cert loading
httpie/compat.py
httpie/ssl_.py

## Jakub Roztocil (jakub@roztocil.co) on 2024-11-01: Cleanup default cert loading
httpie/ssl_.py

## Adam Williamson (adam@blueradius.ca) on 2024-11-01: Explicitly load default certificates when creating SSL context (#1583) (#1596)
httpie/ssl_.py
setup.cfg

## Nguyß╗àn Hß╗ông Qu├ón (ng.hong.quan@gmail.com) on 2024-10-31: Fix link to CurliPie tool (#1582)
docs/README.md

## Dennis Heinrich (der@dennis-heinri.ch) on 2024-10-31: Added an alias for HTTPS in fish completions (#1598)
extras/httpie-completion.fish

## Arthur (82575487+arthur-mountain@users.noreply.github.com) on 2024-11-01: Update the raw json fields example (#1606)
docs/README.md

## Andr├⌐ Srinivasan (andre.srinivasan@gmail.com) on 2024-10-28: Update the Forms section of README.md (#1593)
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2024-07-10: Cleanup
CHANGELOG.md

## Jakub Roztocil (jakub@roztocil.co) on 2024-07-10: Fix SSL connections by pinning the `requests` version to `2.31.0`
CHANGELOG.md
extras/man/http.1
extras/man/httpie.1
extras/man/https.1
httpie/__init__.py
setup.cfg

## Jakub Roztocil (jakub@roztocil.co) on 2024-03-18: Re-add conditional colorama dependency
setup.cfg

## Mathieu Dupuy (deronnax@gmail.com) on 2024-03-18: Migrate setup.py to setup.cfg (#1553)
Makefile
setup.cfg
setup.py
tests/utils/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2024-03-04: Cleanup
tests/conftest.py
tests/test_auth.py
tests/test_binary.py
tests/test_cli.py
tests/test_compress.py
tests/test_config.py
tests/test_cookie_on_redirects.py
tests/test_defaults.py
tests/test_downloads.py
tests/test_encoding.py
tests/test_exit_status.py
tests/test_output.py
tests/test_redirects.py
tests/test_regressions.py
tests/test_sessions.py
tests/test_stream.py
tests/test_uploads.py
tests/test_windows.py
tests/utils/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2024-03-04: Drop dependency on the abandoned python-lazy-fixture II.
tests/conftest.py
tests/fixtures/pytest_lazy_fixture.py
tests/test_cookie_on_redirects.py
tests/test_sessions.py
tests/test_update_warnings.py

## Jakub Roztocil (jakub@roztocil.co) on 2024-03-04: Drop dependency on the abandoned python-lazy-fixture
setup.py
tests/conftest.py
tests/fixtures/pytest_lazy_fixture.py

## Aliaksei Urbanski (aliaksei.urbanski@gmail.com) on 2024-03-04: Ensure support for Python 3.11/3.12 (#1540)
.github/workflows/tests.yml
setup.py

## Aolin (aolinz@outlook.com) on 2024-03-04: docs: fix typo (#1548)
docs/README.md

## github-actions[bot] (41898282+github-actions[bot]@users.noreply.github.com) on 2024-03-04: [automated] Update generated content (#1566)
docs/README.md

## Matthieu LAURENT (matthieu.laurent69@protonmail.com) on 2024-03-04: docs: Update the url for offline mode (#1556)
README.md

## vostok92 (540339+vostok92@users.noreply.github.com) on 2024-03-04: Replace redirection with tee command with sudo for file creation (#1557)
docs/installation/methods.yml

## Jakub Roztocil (jakub@roztocil.co) on 2023-10-24: Update README.md
README.md

## github-actions[bot] (41898282+github-actions[bot]@users.noreply.github.com) on 2023-08-06: [automated] Update generated content (#1524)
extras/man/http.1
extras/man/https.1

## Jakub Roztocil (jakub@roztocil.co) on 2023-08-06: Update README.md
README.md

## Jakub Roztocil (jakub@roztocil.co) on 2023-08-06: Rename repo from `httpie/httpie` to `httpie/cli`
.github/workflows/release-linux-standalone.yml
AUTHORS.md
CHANGELOG.md
CONTRIBUTING.md
MANIFEST.in
README.md
docs/README.md
docs/packaging/README.md
docs/packaging/brew/README.md
docs/packaging/brew/httpie.rb
docs/packaging/linux-arch/PKGBUILD
docs/packaging/linux-debian/README.md
docs/packaging/linux-fedora/README.md
docs/packaging/linux-fedora/httpie.spec.txt
docs/packaging/mac-ports/README.md
docs/packaging/snapcraft/README.md
docs/packaging/windows-chocolatey/README.md
docs/packaging/windows-chocolatey/httpie.nuspec
extras/man/http.1
extras/man/https.1
extras/packaging/linux/README.md
extras/profiling/README.md
extras/profiling/run.py
httpie/cli/definition.py
httpie/client.py
httpie/downloads.py
httpie/plugins/builtin.py
httpie/ssl_.py
setup.cfg
setup.py
snapcraft.yaml
tests/README.md
tests/test_auth.py
tests/test_defaults.py
tests/test_httpie.py
tests/test_output.py
tests/test_redirects.py
tests/test_regressions.py
tests/test_sessions.py
tests/test_ssl.py

## Rudolf Olah (89982117+rudolfolah@users.noreply.github.com) on 2023-05-24: README.md: fix the file based separators internal link (#1510)
docs/README.md

## Boris Verkhovskiy (boris.verk@gmail.com) on 2023-05-23: Document restriction on top-level JSON types explicitly (#1496)
docs/README.md

## github-actions[bot] (41898282+github-actions[bot]@users.noreply.github.com) on 2023-05-22: [automated] Update generated content (#1509)
extras/man/http.1
extras/man/https.1

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-22: Man page clean-up (#1508)
.github/workflows/content.yml
Makefile
extras/man/http.1
extras/man/https.1
extras/scripts/generate_man_pages.py
httpie/cli/definition.py
httpie/output/ui/man_pages.py

## github-actions[bot] (41898282+github-actions[bot]@users.noreply.github.com) on 2023-05-22: [automated] Update auto-generated files (#1507)
docs/README.md
extras/man/http.1
extras/man/httpie.1
extras/man/https.1

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-22: Remove skipping
.github/workflows/autogenerated-files.yml

## chrysle (fritzihab@posteo.de) on 2023-05-22: Fixed installation steps for Debian & Ubuntu (#1473) (#1475)
docs/installation/methods.yml

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-22: Ensure `sudo` for `apt`
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-22: Fix Choco changelog link
docs/packaging/windows-chocolatey/httpie.nuspec

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-22: Fix Snap publish action
.github/workflows/release-snap.yml

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-22: Bump version for Chocolatey
docs/packaging/windows-chocolatey/httpie.nuspec

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-20: Trigger docs deploy
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-20: Fix docs deploy
.github/workflows/docs-deploy.yml

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-19: Add a changelog entry for #1502
CHANGELOG.md
docs/README.md

## Abdelhakim Qbaich (abdelq@users.noreply.github.com) on 2023-05-19: Avoid override of headers by urllib3 when unset (#1502)
httpie/client.py
httpie/models.py
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-19: Fix issue link
CHANGELOG.md

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-19: v3.2.2
CHANGELOG.md
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-19: Flake8
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-19: Skip a test failing in CI
tests/test_plugins_cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-19: Generate default ciphers using approach from #1501
httpie/cli/definition.py
httpie/ssl_.py
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-19: Fix a failing test
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-19: Fix log level display on newer Python
httpie/context.py

## Jakub Roztocil (jakub@roztocil.co) on 2023-05-19: Clean up `DEFAULT_SSL_CIPHERS` comments
httpie/ssl_.py

## C-A de Salaberry (cadesalaberry@yahoo.com) on 2023-05-19: fix(urllib3): :bug: could not find urllib3 DEFAULT_CIPHERS (#1505)
httpie/ssl_.py

## Sid (122173059+hugo-sid@users.noreply.github.com) on 2023-05-09: docs: improve documentation for installation of unstable version (#1490)
docs/README.md

## dependabot[bot] (49699333+dependabot[bot]@users.noreply.github.com) on 2023-03-28: Bump actions/stale from 7 to 8 (#1492)
.github/workflows/stale.yml

## Sid (122173059+hugo-sid@users.noreply.github.com) on 2023-03-23: docs: improve clarity of sentences (#1489)
docs/README.md

## Nishant Sikarwar (nsikarwar@ch.iitr.ac.in) on 2023-01-16: Remove redundant imports (#1466)
httpie/manager/__main__.py
httpie/manager/compat.py

## Jakub Roztocil (jakub@roztocil.co) on 2023-01-15: Fix failing tests with responses ΓëÑ 0.22.0
httpie/models.py

## dependabot[bot] (49699333+dependabot[bot]@users.noreply.github.com) on 2023-01-04: Bump mislav/bump-homebrew-formula-action from 1 to 2 (#1453)
.github/workflows/release-brew.yml

## dependabot[bot] (49699333+dependabot[bot]@users.noreply.github.com) on 2023-01-04: Bump actions/stale from 6 to 7 (#1459)
.github/workflows/stale.yml

## TAKAHASHI Shuuji (shuuji3@gmail.com) on 2023-01-04: Fix ci status badge error (#1464)
README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-10-01: Update README.md
README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-10-01: Clean up and refactor nested JSON parsing & interpreting (#1440)
extras/scripts/generate_man_pages.py
httpie/cli/dicts.py
httpie/cli/nested_json.py
httpie/cli/nested_json/__init__.py
httpie/cli/nested_json/errors.py
httpie/cli/nested_json/interpret.py
httpie/cli/nested_json/parse.py
httpie/cli/nested_json/tokens.py
httpie/cli/requestitems.py
httpie/client.py
httpie/core.py
httpie/utils.py
tests/test_json.py

## Ben Chatelain (phatblat@users.noreply.github.com) on 2022-10-01: ≡ƒöÑ Remove $ from code fenced examples on readme (#1435)
README.md

## Kian-Meng Ang (kianmeng.ang@gmail.com) on 2022-10-01: Fix typos (#1431)
docs/contributors/README.md
docs/installation/generate.py
extras/profiling/benchmarks.py

## a1346054 (36859588+a1346054@users.noreply.github.com) on 2022-10-01: Use `grep -E` instead of `egrep` (#1436)
Makefile

## dependabot[bot] (49699333+dependabot[bot]@users.noreply.github.com) on 2022-10-01: Bump actions/stale from 5 to 6 (#1437)
.github/workflows/stale.yml

## Jakub Roztocil (jakub@roztocil.co) on 2022-08-10: Update README.md
README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-08-10: Update README.md
README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-08-10: Update README.md
README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-08-10: Update README.md
README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-08-10: Update README.md
README.md

## Motahhar Mokfi (78138597+motahharm@users.noreply.github.com) on 2022-07-12: place the logo in the middle in README.md (#1393)
README.md

## Tim Gates (tim.gates@iress.com) on 2022-07-03: docs: Fix a few typos (#1419)
extras/profiling/benchmarks.py
httpie/output/ui/rich_utils.py

## Girish Sharma (girishsharma001@gmail.com) on 2022-06-19: Fix paths to run benchmarking script (#1416)
CONTRIBUTING.md
extras/profiling/README.md
extras/profiling/run.py

## Nate Prewitt (nate.prewitt@gmail.com) on 2022-06-17: Update Requests documentation links (#1414)
docs/README.md

## dependabot[bot] (49699333+dependabot[bot]@users.noreply.github.com) on 2022-06-09: Bump actions/setup-python from 3 to 4 (#1412)
.github/workflows/autogenerated-files.yml
.github/workflows/benchmark.yml
.github/workflows/code-style.yml
.github/workflows/coverage.yml
.github/workflows/release-linux-standalone.yml
.github/workflows/release-pypi.yml
.github/workflows/tests.yml

## Jakub Roztocil (jakub@roztocil.co) on 2022-06-07: Cleanup
httpie/cli/constants.py
httpie/cli/nested_json.py
httpie/client.py

## Jakub Roztocil (jakub@roztocil.co) on 2022-06-07: Have naked `$ make` list all tasks
CONTRIBUTING.md
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2022-06-07: Install `.[test]` reqs in `make install-reqs`
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2022-06-07: Fix installation
docs/installation/methods.yml

## SADIK KUZU (sadikkuzu@hotmail.com) on 2022-05-19: Fix typos in comment lines (#1405)
httpie/internal/daemons.py
httpie/utils.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-16: Package man pages into the deb packages as well. (#1403)
extras/packaging/linux/build.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-16: Fix a misput backtick
docs/README.md

## Jan Brasna (1784648+janbrasna@users.noreply.github.com) on 2022-05-10: Improve single-binary method wording (#1399)
docs/README.md
docs/installation/methods.yml

## Standa Opichal (opichals@gmail.com) on 2022-05-09: Typo fix (#1397)
docs/packaging/brew/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-09: Fix-up standalone binary docs. (#1396)
docs/README.md
docs/installation/methods.yml

## Jannik Vieten (me@exploide.net) on 2022-05-09: updated fish completions for httpie 3.2.1 (#1394)
extras/httpie-completion.fish

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-09: Update release-linux-standalone.yml
.github/workflows/release-linux-standalone.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-09: Standalone binary documentation.
docs/README.md
docs/installation/methods.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-06: Use the proper directory name for the choco action. (#1392)
.github/workflows/release-choco.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-06: Update the chocolatey spec (#1391)
docs/packaging/windows-chocolatey/httpie.nuspec

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-06: Automatically attach debian packages and linux binaries to the release (#1390)
.github/workflows/release-linux-standalone.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-06: Changelog for 3.2.1
CHANGELOG.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-06: Mask the stdout/stderr for the inner daemon process on MacOS (#1389)
CHANGELOG.md
extras/man/http.1
extras/man/httpie.1
extras/man/https.1
httpie/__init__.py
httpie/internal/daemon_runner.py
httpie/internal/daemons.py

## Brian Egleston (github@kamash.com) on 2022-05-06: Checking headers to determine auto-streaming (#1383)
httpie/output/writer.py
tests/test_stream.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-05: Use make install to get the dependencies as well
.github/workflows/release-pypi.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-05: Create the virtual env for the build action.
.github/workflows/release-pypi.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-05: Final release prep for 3.2.0 (#1387)
CHANGELOG.md
extras/man/http.1
extras/man/httpie.1
extras/man/https.1
httpie/__init__.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-05: Add missing changelog entries (#1386)
CHANGELOG.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-05: Contributors for 3.2.0 (#1374)
docs/contributors/fetch.py
docs/contributors/generate.py
docs/contributors/people.json
docs/contributors/snippet.jinja2

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-05: Automatic release update warnings. (#1336)
.github/workflows/release-pypi.yml
Makefile
docs/README.md
extras/packaging/linux/Dockerfile
extras/packaging/linux/build.py
httpie/config.py
httpie/core.py
httpie/internal/__build_channel__.py
httpie/internal/__init__.py
httpie/internal/daemon_runner.py
httpie/internal/daemons.py
httpie/internal/update_warnings.py
httpie/manager/cli.py
httpie/manager/tasks/__init__.py
httpie/manager/tasks/check_updates.py
httpie/manager/tasks/sessions.py
httpie/utils.py
setup.py
tests/test_update_warnings.py
tests/test_uploads.py
tests/utils/__init__.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-05: Man page fixes (#1364)
docs/README.md
extras/man/http.1
extras/man/httpie.1
extras/man/https.1
extras/scripts/generate_man_pages.py
httpie/cli/definition.py
httpie/cli/options.py
httpie/manager/cli.py
httpie/output/ui/man_pages.py
httpie/output/ui/rich_help.py
httpie/output/ui/rich_palette.py
httpie/output/ui/rich_utils.py
setup.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-05: Hide pretty help (#1384)
httpie/cli/argparser.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-05: Don't make bold the default for pie themes (#1385)
httpie/output/ui/palette.py
httpie/output/ui/rich_palette.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-05: Update installation instructions for debian (#1373)
docs/README.md
docs/installation/methods.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-05: Refactor palette (#1378)
httpie/context.py
httpie/core.py
httpie/output/formatters/colors.py
httpie/output/ui/man_pages.py
httpie/output/ui/palette.py
httpie/output/ui/rich_help.py
httpie/output/ui/rich_palette.py
httpie/output/ui/rich_progress.py
httpie/output/ui/rich_utils.py
httpie/sessions.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-03: Deprecate --history-print (#1380)
docs/README.md
extras/man/http.1
extras/man/https.1
httpie/cli/definition.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-05-03: Use sentence case for the group names in the parser (#1381)
httpie/cli/definition.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-04-28: Skip on pyOpenSSL (#1376)
tests/conftest.py
tests/test_ssl.py
tests/utils/__init__.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-04-28: Disable PackIt CI on the PRs (#1375)
.packit.yaml

## luzpaz (luzpaz@users.noreply.github.com) on 2022-04-15: Fix typos (user-facing and non-user-facing) (#1357)
.github/workflows/release-snap.yml
extras/packaging/linux/README.md
extras/profiling/README.md
extras/profiling/benchmarks.py
httpie/context.py
httpie/manager/tasks/plugins.py
httpie/plugins/manager.py
tests/test_cli_utils.py
tests/test_plugins_cli.py
tests/utils/__init__.py

## dependabot[bot] (49699333+dependabot[bot]@users.noreply.github.com) on 2022-04-15: Bump peter-evans/create-pull-request from 3 to 4 (#1355)
.github/workflows/autogenerated-files.yml

## Jakub Roztocil (jakub@roztocil.co) on 2022-04-14: Explain that we lost 54k stars in the README with a link to blog post
README.md
docs/stardust.png

## Batuhan Taskaya (isidentical@gmail.com) on 2022-04-14: Single binary executables (#1330)
.github/workflows/release-linux-standalone.yml
.gitignore
docs/markdownlint.rb
docs/packaging/README.md
docs/packaging/brew/README.md
docs/packaging/brew/brew-deps.py
docs/packaging/brew/httpie.rb
docs/packaging/brew/update.sh
docs/packaging/linux-debian/README.md
docs/packaging/linux-fedora/httpie.spec.txt
docs/packaging/linux-fedora/update.sh
docs/packaging/snapcraft/README.md
docs/packaging/windows-chocolatey/README.md
extras/packaging/linux/Dockerfile
extras/packaging/linux/README.md
extras/packaging/linux/build.py
extras/packaging/linux/get_release_artifacts.sh
extras/packaging/linux/scripts/hooks/hook-pip.py
extras/packaging/linux/scripts/http_cli.py
extras/packaging/linux/scripts/httpie_cli.py
httpie/compat.py
httpie/manager/compat.py
httpie/manager/tasks/plugins.py
httpie/plugins/manager.py
httpie/utils.py
setup.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-04-14: Don't block users with the warning thread. (#1350)
CHANGELOG.md
httpie/uploads.py
tests/test_uploads.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-04-14: [Major] UI Enhancements (#1321)
.github/workflows/autogenerated-files.yml
.github/workflows/docs-update-install.yml
Makefile
extras/man/http.1
extras/man/httpie.1
extras/man/https.1
extras/scripts/generate_man_pages.py
httpie/__init__.py
httpie/cli/argparser.py
httpie/cli/definition.py
httpie/cli/options.py
httpie/cli/utils.py
httpie/context.py
httpie/core.py
httpie/downloads.py
httpie/manager/cli.py
httpie/output/formatters/colors.py
httpie/output/ui/man_pages.py
httpie/output/ui/palette.py
httpie/output/ui/rich_help.py
httpie/output/ui/rich_palette.py
httpie/output/ui/rich_progress.py
httpie/output/ui/rich_utils.py
setup.py
tests/test_cli_ui.py
tests/test_cli_utils.py
tests/test_downloads.py
tests/test_output.py
tests/test_parser_schema.py
tests/test_stream.py
tests/utils/__init__.py
tests/utils/plugins_cli.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-04-14: Add support for sending secure cookies over localhost (#1327)
CHANGELOG.md
httpie/compat.py
httpie/cookies.py
httpie/sessions.py
tests/conftest.py
tests/test_cookie_on_redirects.py
tests/test_sessions.py
tests/utils/__init__.py
tests/utils/http_server.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-04-14: Use the raw request version when the original is not accessible (#1352)
httpie/models.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-04-14: Limit concurrency of our test workflow (#1353)
.github/workflows/tests.yml

## dependabot[bot] (49699333+dependabot[bot]@users.noreply.github.com) on 2022-04-11: Bump actions/stale from 4 to 5 (#1347)
.github/workflows/stale.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-04-03: Implement support for multiple headers with the same name in sessions (#1335)
CHANGELOG.md
httpie/cli/dicts.py
httpie/legacy/v3_1_0_session_cookie_format.py
httpie/legacy/v3_2_0_session_header_format.py
httpie/manager/tasks/sessions.py
httpie/sessions.py
tests/fixtures/session_data/new/cookies_dict.json
tests/fixtures/session_data/new/cookies_dict_dev_version.json
tests/fixtures/session_data/new/cookies_dict_with_extras.json
tests/fixtures/session_data/new/empty_cookies_dict.json
tests/fixtures/session_data/new/empty_cookies_list.json
tests/fixtures/session_data/new/empty_headers_dict.json
tests/fixtures/session_data/new/empty_headers_list.json
tests/fixtures/session_data/new/headers_cookies_dict_mixed.json
tests/fixtures/session_data/new/headers_dict.json
tests/fixtures/session_data/new/headers_dict_extras.json
tests/fixtures/session_data/new/headers_list.json
tests/fixtures/session_data/old/cookies_dict.json
tests/fixtures/session_data/old/cookies_dict_dev_version.json
tests/fixtures/session_data/old/cookies_dict_with_extras.json
tests/fixtures/session_data/old/empty_cookies_dict.json
tests/fixtures/session_data/old/empty_cookies_list.json
tests/fixtures/session_data/old/empty_headers_dict.json
tests/fixtures/session_data/old/empty_headers_list.json
tests/fixtures/session_data/old/headers_cookies_dict_mixed.json
tests/fixtures/session_data/old/headers_dict.json
tests/fixtures/session_data/old/headers_dict_extras.json
tests/fixtures/session_data/old/headers_list.json
tests/test_sessions.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-04-03: Add `httpie cli plugins` in favor of the new cli namespace. (#1320)
CHANGELOG.md
docs/README.md
httpie/manager/cli.py
httpie/manager/core.py
httpie/manager/tasks/__init__.py
httpie/manager/tasks/export_args.py
httpie/manager/tasks/plugins.py
httpie/manager/tasks/sessions.py
tests/test_plugins_cli.py
tests/utils/plugins_cli.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-04-03: Don't send `Content-Length` for `OPTIONS` requests when there is no data. (#1319)
CHANGELOG.md
httpie/__init__.py
httpie/cli/constants.py
httpie/client.py
tests/test_httpie.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-04-01: Ping werkzeug to <2.1.0 (#1345)
setup.py

## dependabot[bot] (49699333+dependabot[bot]@users.noreply.github.com) on 2022-03-22: Bump peter-evans/create-or-update-comment from 1 to 2 (#1332)
.github/workflows/benchmark.yml

## dependabot[bot] (49699333+dependabot[bot]@users.noreply.github.com) on 2022-03-22: Bump peter-evans/find-comment from 1 to 2 (#1333)
.github/workflows/benchmark.yml

## Jakub Roztocil (jakub@roztocil.co) on 2022-03-14: Fix/tweak docs
docs/README.md

## Ethan Mills (ethan.mills@hotmail.co.uk) on 2022-03-12: Fix broken docs link (#1322)
docs/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-09: Integrate automatic releases. (#1315)
.github/workflows/release-brew.yml
.github/workflows/release-choco.yml
.github/workflows/release-pypi.yml
.github/workflows/release-snap.yml
.github/workflows/release.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-08: Add table headers for upgrade flags (#1314)
docs/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-08: Update chocolatey for release
docs/packaging/windows-chocolatey/httpie.nuspec

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-08: Release prep for 3.1.0 (#1313)
CHANGELOG.md
docs/README.md
httpie/__init__.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-08: Decouple parser definition from argparse (#1293)
docs/README.md
httpie/cli/constants.py
httpie/cli/definition.py
httpie/cli/options.py
httpie/core.py
httpie/manager/cli.py
httpie/manager/tasks.py
httpie/output/models.py
httpie/output/streams.py
httpie/output/writer.py
tests/test_httpie_cli.py
tests/test_parser_schema.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-07: Fix documentation styling errors.
docs/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-07: Change error messages to use a better format.
httpie/manager/tasks.py

## Jakub Roztocil (jakub@roztocil.co) on 2022-03-07: Tweak
SECURITY.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-03-07: Tweak SECURITY and add a Security policy section to docs
SECURITY.md
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-03-07: Polish sessions docs
docs/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-04: Apply suggestions from the review
SECURITY.md
docs/README.md
httpie/legacy/__init__.py
httpie/legacy/cookie_format.py
httpie/manager/cli.py
httpie/manager/tasks.py
httpie/sessions.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-01: Implement new style cookies
docs/README.md
httpie/client.py
httpie/config.py
httpie/manager/cli.py
httpie/manager/core.py
httpie/manager/tasks.py
httpie/sessions.py
httpie/utils.py
setup.py
tests/conftest.py
tests/fixtures/__init__.py
tests/fixtures/session_data/new/cookies_dict.json
tests/fixtures/session_data/new/cookies_dict_dev_version.json
tests/fixtures/session_data/new/cookies_dict_with_extras.json
tests/fixtures/session_data/new/empty_cookies_dict.json
tests/fixtures/session_data/new/empty_cookies_list.json
tests/fixtures/session_data/old/cookies_dict.json
tests/fixtures/session_data/old/cookies_dict_dev_version.json
tests/fixtures/session_data/old/cookies_dict_with_extras.json
tests/fixtures/session_data/old/empty_cookies_dict.json
tests/fixtures/session_data/old/empty_cookies_list.json
tests/test_cookie_on_redirects.py
tests/test_httpie_cli.py
tests/test_plugins_cli.py
tests/test_sessions.py
tests/utils/__init__.py
tests/utils/http_server.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-07: Fix the tests with the latest layout
tests/test_cli_ui.py

## Jakub Roztocil (jakub@roztocil.co) on 2022-03-07: Tweak compact help
httpie/cli/argparser.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-08: Make the naked invocation display a compacted help
CHANGELOG.md
httpie/cli/argparser.py
tests/test_cli_ui.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-07: Mention about interactive prompt on key passphrases
httpie/cli/definition.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-01: Implement support for private key passphrases
CHANGELOG.md
docs/README.md
httpie/cli/argparser.py
httpie/cli/argtypes.py
httpie/cli/definition.py
httpie/client.py
httpie/ssl_.py
tests/client_certs/password_protected/client.key
tests/client_certs/password_protected/client.pem
tests/test_ssl.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-07: Style fix on the changelog
CHANGELOG.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-07: Add changelog entry
CHANGELOG.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-03-03: Update httpie/uploads.py
httpie/uploads.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-25: Prevent data race happening between `select.select` and `file.read()`
httpie/uploads.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-07: Introduce a mode to suppress all warnings (#1283)
CHANGELOG.md
httpie/cli/argparser.py
httpie/context.py
httpie/core.py
tests/test_output.py
tests/utils/__init__.py

## Hoylen Sue (hoylen@hoylen.com) on 2022-03-04: Replaced unmaintained OAuth plugin with new httpie-oauth1 plugin. (#1302)
docs/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-03-03: Fix displaying of status code without a status message. (#1301)
CHANGELOG.md
httpie/output/lexers/http.py
tests/test_output.py
tests/utils/__init__.py
tests/utils/http_server.py

## dependabot[bot] (49699333+dependabot[bot]@users.noreply.github.com) on 2022-03-03: Bump actions/checkout from 2 to 3 (#1311)
.github/workflows/benchmark.yml
.github/workflows/code-style.yml
.github/workflows/coverage.yml
.github/workflows/docs-check-markdown.yml
.github/workflows/docs-update-install.yml
.github/workflows/release-snap.yml
.github/workflows/release.yml
.github/workflows/test-package-linux-snap.yml
.github/workflows/test-package-mac-brew.yml
.github/workflows/tests.yml

## dependabot[bot] (49699333+dependabot[bot]@users.noreply.github.com) on 2022-03-01: Bump actions/setup-python from 2 to 3 (#1307)
.github/workflows/benchmark.yml
.github/workflows/code-style.yml
.github/workflows/coverage.yml
.github/workflows/docs-update-install.yml
.github/workflows/release.yml
.github/workflows/tests.yml

## Sebastian Stasiak (arionw@live.com) on 2022-02-28: Update commands for Arch (#1306)
docs/README.md
docs/installation/methods.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-25: Add a changelog entry for the top-level array regulation
CHANGELOG.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-09: Regulate top-level arrays (#1292)
docs/README.md
httpie/cli/constants.py
httpie/cli/dicts.py
httpie/cli/nested_json.py
httpie/client.py
tests/test_json.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-08: Disable additional repos
.packit.yaml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-08: Fix the packit syntax
.packit.yaml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-08: Leave a note for the local spec
.packit.yaml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-08: Update the local copy fore 3.0.2
docs/packaging/linux-fedora/httpie.spec.txt

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-08: Use the lastest fedora spec in the packit
.packit.yaml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-05: Update copyright year
docs/packaging/windows-chocolatey/httpie.nuspec

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-05: Point package to 3.0.2
docs/packaging/windows-chocolatey/httpie.nuspec

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-05: Use 3.0.0 blog post as the changelog
docs/packaging/windows-chocolatey/httpie.nuspec

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-03: Make the version point to `3.0.3.dev0` (#1291)
CHANGELOG.md
docs/README.md
httpie/__init__.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-01: Fix escaping of integer indexes with multiple backslashes (#1288)
CHANGELOG.md
httpie/cli/nested_json.py
tests/test_json.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-02-01: Mark stdin warning related tests with `requires_external_processes` (#1289)
pytest.ini
tests/test_uploads.py

## Marcos Chicote (totochicote@gmail.com) on 2022-01-26: 2022 (#1259)
LICENSE

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-26: Finish off the naming
.github/workflows/release.yml
.github/workflows/test-package-linux-snap.yml
.github/workflows/test-package-mac-brew.yml
.github/workflows/tests.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-26: Proper naming for the release runs
.github/workflows/docs-deploy.yml
.github/workflows/docs-update-install.yml
.github/workflows/release-snap.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-26: Add names to the CI runners
.github/workflows/code-style.yml
.github/workflows/coverage.yml
.github/workflows/docs-check-markdown.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-26: Add level parameter to the snap releaser (#1282)
.github/workflows/release-snap.yml

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-24: Update CHANGELOG.md
CHANGELOG.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-24: Update CHANGELOG.md
CHANGELOG.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-24: Update CHANGELOG.md
CHANGELOG.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: Release 3.0.2 (#1281)
CHANGELOG.md
httpie/__init__.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: Dont apply default options on the httpie command (#1280)
httpie/core.py
httpie/manager/__main__.py
pytest.ini
tests/test_plugins_cli.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: docs: format the benchmark docs
extras/profiling/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: fix lint errors
extras/profiling/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: Document the pyOpenSSL option
extras/profiling/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: docs: add --{local, target}-{repo, branch} / format
extras/profiling/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: docs: document the --fresh option
extras/profiling/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: Describe the usage for benchmarks
extras/profiling/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: docs: add requirements
extras/profiling/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: docs: mention about the runners
extras/profiling/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: docs: give a brief description
extras/profiling/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: docs: fix the title to `benchmarking infrastructure`
extras/profiling/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: docs: add initial benchmark docs
extras/profiling/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-24: docs: fix the nested json example (#1278)
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-24: Typos
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-23: Update CHANGELOG.md
CHANGELOG.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-23: Update CHANGELOG.md
CHANGELOG.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-23: Tweak nested JSON docs
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-23: Tweak auth docs
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-23: Document auto-stream
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-23: Docs
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-23: Docs
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-23: Tweak response meta docs
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-23: Update cached brew formula
docs/packaging/brew/httpie.rb

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-23: 3.0.1
CHANGELOG.md
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-23: Fix time elapsed (#1277)
docs/README.md
docs/markdownlint.rb
httpie/client.py
httpie/models.py
httpie/output/formatters/colors.py
httpie/output/lexers/metadata.py
httpie/output/ui/palette.py
tests/test_meta.py
tests/test_output.py
tests/utils/matching/test_matching.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-23: Update the contributors (#1275)
docs/contributors/people.json

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-21: Display the latest docs (#1274)
docs/config.json

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-21: Fix `make brew-test`
Makefile

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-21: Update brew with 3.0 (#1273)
docs/packaging/brew/httpie.rb

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-21: 3.0 release prep (#1272)
CHANGELOG.md
docs/README.md
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2022-01-21: Finish docs for v3.0.0 (#1269)
CHANGELOG.md
docs/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-14: Remove 3.6 support / discontinue less available platforms  (#1267)
.github/workflows/test-package-linux-snap.yml
.github/workflows/tests.yml
CHANGELOG.md
CONTRIBUTING.md
docs/README.md
docs/installation/methods.yml
docs/packaging/README.md
docs/packaging/linux-alpine/APKBUILD
docs/packaging/linux-alpine/README.md
docs/packaging/linux-aosc/README.md
docs/packaging/linux-aosc/autobuild/defines
docs/packaging/linux-aosc/spec
docs/packaging/linux-gentoo/Manifest
docs/packaging/linux-gentoo/README.md
docs/packaging/linux-gentoo/httpie-2.6.0.ebuild
docs/packaging/linux-gentoo/metadata.xml
docs/packaging/linux-void/README.md
docs/packaging/linux-void/template
docs/packaging/mac-ports/Portfile
docs/packaging/spack/README.md
docs/packaging/spack/package.py
docs/packaging/windows-chocolatey/httpie.nuspec
httpie/plugins/manager.py
setup.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-14: Change the default style for windows from fruity to auto (#1268)
CHANGELOG.md
httpie/output/formatters/colors.py
tests/test_json.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-14: Update the brew file
docs/packaging/brew/httpie.rb

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-13: use constants
httpie/cli/constants.py
httpie/cli/nested_json.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-12: Use enums
httpie/cli/nested_json.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-07: A few edits
docs/README.md
httpie/cli/nested_json.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-07: Rewrite the docs
docs/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-07: Implement escaped integers
httpie/cli/nested_json.py
tests/test_json.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-04: Implement HTTPie Nested JSON v2
httpie/cli/argtypes.py
httpie/cli/constants.py
httpie/cli/json_form.py
httpie/cli/nested_json.py
httpie/cli/requestitems.py
httpie/core.py
tests/test_json.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-13: Proper separation of meta/body
httpie/output/streams.py
httpie/output/writer.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-13: Make the stdin wait tests more reliable
tests/test_uploads.py

## Batuhan Taskaya (isidentical@gmail.com) on 2022-01-12: Add warnings when there is no incoming data from stdin (#1256)
CHANGELOG.md
httpie/client.py
httpie/core.py
httpie/uploads.py
tests/test_uploads.py

## Greg Myers (myersg86@gmail.com) on 2022-01-10: Fix two typos in docs/README.md (#1261)
docs/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-29: Fix --raw with --chunked (#1254)
CHANGELOG.md
httpie/client.py
httpie/uploads.py
tests/test_uploads.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-29: Mention explicitly about prompted passwords are stored as raw in the docs
docs/README.md

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-29: Include the original issue in the changelog
CHANGELOG.md

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-29: Add the changelog entry
CHANGELOG.md

## Sebastian Czech (sebaczech@gmail.com) on 2021-12-29: Store prompted passwords in local sessions (#1239)
httpie/cli/argparser.py
tests/test_sessions.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-24: Update shortcuts as well
httpie/cli/definition.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-24: Mention about levels in -v
httpie/cli/definition.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-24: Fix -v docs to include BASE_OUTPUT_OPTIONS
httpie/cli/definition.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-24: Include response metadata in --print help
httpie/cli/definition.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-23: Implement basic metrics layout & total elapsed time (#1250)
CHANGELOG.md
docs/README.md
httpie/cli/argparser.py
httpie/cli/constants.py
httpie/cli/definition.py
httpie/core.py
httpie/downloads.py
httpie/models.py
httpie/output/formatters/colors.py
httpie/output/lexers/common.py
httpie/output/lexers/http.py
httpie/output/lexers/metadata.py
httpie/output/processing.py
httpie/output/streams.py
httpie/output/writer.py
httpie/plugins/base.py
tests/test_downloads.py
tests/test_meta.py
tests/test_output.py
tests/test_tokens.py
tests/utils/matching/parsing.py
tests/utils/matching/test_matching.py
tests/utils/matching/tokens.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-23: Better DNS error handling (#1249)
CHANGELOG.md
httpie/core.py
httpie/utils.py
tests/test_errors.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-23: Formalize @ suffix for all operators (#1225)
docs/README.md
httpie/cli/constants.py
httpie/cli/requestitems.py
tests/test_cli.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-23: Optimize encoding detection (#1243)
extras/profiling/benchmarks.py
httpie/encoding.py
httpie/output/streams.py
tests/fixtures/__init__.py
tests/test_stream.py
tests/utils/http_server.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-21: Test `https` as well
docs/packaging/brew/httpie.rb

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-21: Test httpie
docs/packaging/brew/httpie.rb

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-21: Make brew action triggerable
.github/workflows/test-package-mac-brew.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-21: Make snap action triggerable
.github/workflows/test-package-linux-snap.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-19: Implement new `pie` and `pie-light` styles (#1238)
CHANGELOG.md
docs/README.md
httpie/output/formatters/colors.py
httpie/output/lexers/http.py
httpie/output/ui/__init__.py
httpie/output/ui/palette.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-17: Improve startup time when pyOpenSSL is available on the environment (#1233)
httpie/uploads.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-17: Faster downloads through bigger chunks / less buffering (#1236)
httpie/downloads.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-17: Implement `httpie upgrade` for upgrading plugins (#1241)
docs/README.md
httpie/manager/cli.py
httpie/manager/plugins.py
tests/test_plugins_cli.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-16: Strip out extra variables from the actual mime type (#1244)
CHANGELOG.md
httpie/output/streams.py
tests/test_output.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-16: (stale action) bump operations per run to 300
.github/workflows/stale.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-16: (stale action) get rid of stale message, only comment on closing
.github/workflows/stale.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-16: (stale action) bump days to 30
.github/workflows/stale.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-16: (stale action) Fix typo in closing message
.github/workflows/stale.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-16: Move stale action from debug to actual run
.github/workflows/stale.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-16: Only configure with workflow_dispatch
.github/workflows/stale.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-16: Set stale action to run on workflow dispatch
.github/workflows/stale.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-16: Close all stale PRs (#1245)
.github/workflows/stale.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-14: Don't inconsistently add XML declarations (#1227)
CHANGELOG.md
docs/README.md
httpie/output/formatters/xml.py
tests/fixtures/xmldata/valid/custom-header.xml
tests/fixtures/xmldata/valid/custom-header_formatted.xml
tests/fixtures/xmldata/valid/simple-ns_formatted.xml
tests/fixtures/xmldata/valid/simple-single-tag_formatted.xml
tests/fixtures/xmldata/valid/simple-single-tag_raw.xml
tests/fixtures/xmldata/valid/simple_formatted.xml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-14: Add initial benchmarking infrastructure (#1232)
.github/workflows/benchmark.yml
CONTRIBUTING.md
Makefile
extras/profiling/benchmarks.py
extras/profiling/run.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-09: Remove unnecessary empty line in CHANGELOG
CHANGELOG.md

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-08: Automatically enable --stream on server sent events (#1226)
CHANGELOG.md
httpie/output/writer.py
tests/test_stream.py
tests/utils/http_server.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-08: Ignore crashes that happen on the 3rd party plugins (#1228)
CHANGELOG.md
httpie/plugins/manager.py
tests/conftest.py
tests/test_plugins_cli.py
tests/utils/plugins_cli.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-08: Fix snapcraft packaging (#1235)
snapcraft.yaml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-03: Add nested JSON syntax to the HTTPie DSL (#1224)
CHANGELOG.md
docs/README.md
httpie/cli/constants.py
httpie/cli/definition.py
httpie/cli/json_form.py
httpie/cli/requestitems.py
httpie/client.py
httpie/utils.py
tests/test_cli.py
tests/test_json.py
tests/utils/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-12-01: Changelog
CHANGELOG.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-12-01: CHANGELOG.md
CHANGELOG.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-12-01: CHANGELOG.md
CHANGELOG.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-12-01: Tweak changelog & `3.0.0.dev0`
CHANGELOG.md
httpie/__init__.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-01: Add plugin management changelog entry (#1223)
CHANGELOG.md

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-01: brew: add multidict (#1222)
docs/packaging/brew/brew-deps.py
docs/packaging/brew/httpie.rb

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-01: Improve startup time with lazy loading some args (#1221)
CHANGELOG.md
httpie/cli/definition.py
httpie/cli/utils.py
httpie/output/formatters/colors.py
tests/test_cli_utils.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-01: Support ==@ syntax for query parameter values from file (#1218)
docs/README.md
httpie/cli/constants.py
httpie/cli/requestitems.py
tests/test_cli.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-12-01: Implement Bearer Auth (#1216)
CHANGELOG.md
docs/README.md
httpie/cli/definition.py
httpie/plugins/builtin.py
httpie/plugins/registry.py
tests/test_auth.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-11-30: Fix packit CI (#1219)
.packit.yaml
docs/packaging/linux-fedora/httpie.spec.txt
httpie/manager/plugins.py
setup.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-11-30: Add httpie --version (#1220)
httpie/manager/cli.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-11-30: cmd: Implement httpie plugins interface (#1200)
docs/README.md
docs/markdownlint.rb
httpie/cli/argparser.py
httpie/cli/definition.py
httpie/client.py
httpie/compat.py
httpie/config.py
httpie/context.py
httpie/core.py
httpie/manager/__init__.py
httpie/manager/__main__.py
httpie/manager/cli.py
httpie/manager/core.py
httpie/manager/plugins.py
httpie/plugins/manager.py
httpie/ssl_.py
httpie/utils.py
setup.py
tests/conftest.py
tests/test_plugins_cli.py
tests/test_ssl.py
tests/utils/__init__.py
tests/utils/plugins_cli.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-11-26: Proper JSON handling for :=/:=@ (#1213)
CHANGELOG.md
docs/README.md
httpie/cli/argparser.py
httpie/cli/requestitems.py
tests/test_cli.py
tests/test_json.py

## Vivaan Verma (doublevcodes@gmail.com) on 2021-11-25: Change `PyPi` to `PyPI` (#1203)
docs/README.md
docs/installation/methods.yml

## Batuhan Taskaya (isidentical@gmail.com) on 2021-11-25: core: support custom request/response classes (#1205)
httpie/client.py
httpie/core.py
httpie/models.py
httpie/output/writer.py

## Batuhan Taskaya (isidentical@gmail.com) on 2021-11-25: Preserve individual headers with the same name on responses (#1208)
CHANGELOG.md
httpie/adapters.py
httpie/cli/dicts.py
httpie/cli/requestitems.py
httpie/client.py
httpie/models.py
httpie/sessions.py
httpie/ssl.py
tests/conftest.py
tests/test_cli.py
tests/test_httpie.py
tests/utils/http_server.py

## Jan Bra┼ína (1784648+janbrasna@users.noreply.github.com) on 2021-11-21: Fix README broken links to old locations (#1209)
docs/README.md

## Jan Bra┼ína (1784648+janbrasna@users.noreply.github.com) on 2021-11-21: Consistent userdir/name example (#1210)
CONTRIBUTING.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-11-05: Add `$ http ://` error handling test
tests/test_cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-11-05: Strip leading `://` from URLs to allow quick conversion of a pasted URL to calls (#1197)
CHANGELOG.md
docs/README.md
httpie/cli/argparser.py
tests/test_cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-11-04: Update bug_report.md
.github/ISSUE_TEMPLATE/bug_report.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-11-03: Update config.json
docs/config.json

## Batuhan Taskaya (isidentical@gmail.com) on 2021-10-31: Support multiple headers sharing the same name (#1190)
CHANGELOG.md
docs/README.md
httpie/cli/dicts.py
httpie/cli/requestitems.py
httpie/client.py
httpie/models.py
setup.py
tests/test_cli.py
tests/test_httpie.py
tests/test_redirects.py
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-29: Update README.md
docs/README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-25: Change Chocolatey owner
docs/packaging/windows-chocolatey/httpie.nuspec

## Gaurav (graheja1997@gmail.com) on 2021-10-25: Fix Snap autocompletion (#1189)
extras/httpie-completion.bash
snapcraft.yaml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-25: Change Void Linux maintainer
docs/packaging/linux-void/template

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-25: Update Spack metadata
docs/packaging/spack/package.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-25: Update Gentoo metadata
docs/packaging/linux-gentoo/metadata.xml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-25: Fix Gentoo example link
docs/packaging/linux-gentoo/README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-25: Remove myself from the HTTPie team
docs/contributors/generate.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-25: Add contributors list update to the release process
docs/packaging/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-24: Add HTTPie 2.6.0 blog post link
CHANGELOG.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-19: Tiny docstring clean-up
httpie/cli/argtypes.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-19: Bump the version to 2.7.0.dev0 (#1188)
CHANGELOG.md
docs/README.md
httpie/__init__.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-19: Update downstream files for HTTPie 2.6.0 (#1186)
docs/README.md
docs/packaging/brew/README.md
docs/packaging/brew/httpie.rb
docs/packaging/linux-alpine/APKBUILD
docs/packaging/linux-aosc/autobuild/defines
docs/packaging/linux-arch/PKGBUILD
docs/packaging/linux-debian/README.md
docs/packaging/linux-fedora/httpie.spec.txt
docs/packaging/linux-gentoo/Manifest
docs/packaging/linux-gentoo/README.md
docs/packaging/linux-gentoo/httpie-2.6.0.ebuild
docs/packaging/linux-void/README.md
docs/packaging/linux-void/template
docs/packaging/mac-ports/Portfile
docs/packaging/mac-ports/README.md
docs/packaging/spack/README.md
docs/packaging/spack/package.py
docs/packaging/windows-chocolatey/httpie.nuspec
httpie/__init__.py

## hosseingt (hosseingt@gmail.com) on 2021-10-15: Corrected command for installing development version on Windows (#1187)
CONTRIBUTING.md

## Miro Hron─ìok (miro@hroncok.cz) on 2021-10-15: dnf/yum update is the same as dnf upgrade -- it updates all packages (#1184)
docs/README.md
docs/installation/methods.yml

## Miro Hron─ìok (miro@hroncok.cz) on 2021-10-15: Minor version changes in the Fedora packaging docs (#1185)
docs/packaging/linux-fedora/README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-14: Update the awesome contributors list to HTTPie 2.6.0
docs/contributors/generate.py
docs/contributors/people.json

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-14: Blank `master_and_released_docs_differ_after`
docs/config.json

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-14: Update setup.py
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-14: Update links
setup.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-14: Release workflow: fix
.github/workflows/release.yml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-14: Configure PyPi for the release workflow
.github/workflows/release.yml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-14: v2.6.0 (#1182)
CHANGELOG.md
docs/README.md
httpie/__init__.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-14: Add a script that lists all contributors to a release (#1181)
docs/contributors/README.md
docs/contributors/fetch.py
docs/contributors/generate.py
docs/contributors/people.json
docs/contributors/snippet.jinja2

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-13: Update CHANGELOG.md
CHANGELOG.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-13: Add `--response=mime` and `--response=charset` docs (#1179)
docs/README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-11: Packaging documentation tweaks
docs/packaging/README.md
httpie/output/lexers/json.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-11: Tweak the Chocolatey package installation file
docs/packaging/windows-chocolatey/tools/chocolateyinstall.ps1

## jakubroztocil (jakubroztocil@users.noreply.github.com) on 2021-10-10: Auto-update install docs
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-10: Remove macOS/Snap
docs/installation/methods.yml

## jakubroztocil (jakubroztocil@users.noreply.github.com) on 2021-10-10: Auto-update install docs
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-10: Better links for snap on macos
docs/installation/methods.yml

## jakubroztocil (jakubroztocil@users.noreply.github.com) on 2021-10-10: Auto-update install docs
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-10: Link GitHub action file in generated commit
.github/workflows/docs-update-install.yml
docs/README.md

## jakubroztocil (jakubroztocil@users.noreply.github.com) on 2021-10-10: Auto-update installation instructions in the docs
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-10: Tweak install docs template
.github/workflows/docs-update-install.yml
docs/installation/installation.jinja2

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-08: Add --compress documentation (#1173)
docs/README.md

## dkreeft (37153972+dkreeft@users.noreply.github.com) on 2021-10-08: Added the ability to silence warnings via double `-q` or `--quiet` (#1175)
CHANGELOG.md
docs/README.md
httpie/cli/definition.py
httpie/core.py
tests/test_output.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-08: Add a workflow to control Snap publications (#1176)
.github/workflows/release-snap.yml
.github/workflows/release.yml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-07: Add help output for --chunked (#1174)
httpie/cli/definition.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-07: Update README.md
README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-07: Use HTTPie repository everywhere
docs/README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-07: Remove unused import
httpie/plugins/base.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-07: Add summary to Chocolatey metadata
docs/packaging/windows-chocolatey/httpie.nuspec

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-07: Fix Snapcraft and Spack anchors
docs/packaging/snapcraft/README.md
docs/packaging/spack/README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-07: Specify the API key to submit Chocolatey packages
docs/packaging/windows-chocolatey/README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-07: Add Chocolatey packaging information (#1172)
.gitignore
docs/packaging/README.md
docs/packaging/windows-chocolatey/README.md
docs/packaging/windows-chocolatey/httpie.nuspec
docs/packaging/windows-chocolatey/tools/chocolateyinstall.ps1
docs/packaging/windows-chocolatey/tools/chocolateyuninstall.ps1
snapcraft.yaml

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-06: Tweak
httpie/plugins/base.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-06: Add more types and docs for plugins API II.
httpie/plugins/base.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-06: Add more types and docs for plugins API
httpie/plugins/base.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-06: Update CHANGELOG.md
CHANGELOG.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-06: Ignore more venv folders and VS Code folder
.gitignore

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-06: Fix encoding error with non-prettified encoded responses (#1168)
CHANGELOG.md
docs/README.md
httpie/cli/argparser.py
httpie/cli/argtypes.py
httpie/cli/constants.py
httpie/cli/definition.py
httpie/client.py
httpie/codec.py
httpie/compat.py
httpie/config.py
httpie/constants.py
httpie/context.py
httpie/encoding.py
httpie/models.py
httpie/output/formatters/xml.py
httpie/output/processing.py
httpie/output/streams.py
httpie/output/utils.py
httpie/output/writer.py
httpie/utils.py
tests/fixtures/__init__.py
tests/test_auth.py
tests/test_cli.py
tests/test_config.py
tests/test_encoding.py
tests/test_errors.py
tests/test_httpie.py
tests/test_json.py
tests/test_output.py
tests/test_sessions.py
tests/test_stream.py
tests/test_unicode.py
tests/test_xml.py
tests/utils/__init__.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-06: Add documentation about our release process (#1159)
.github/workflows/test-package-mac-brew.yml
Makefile
docs/packaging/README.md
docs/packaging/brew/README.md
docs/packaging/brew/brew-deps.py
docs/packaging/brew/httpie.rb
docs/packaging/linux-alpine/APKBUILD
docs/packaging/linux-alpine/README.md
docs/packaging/linux-aosc/README.md
docs/packaging/linux-aosc/spec
docs/packaging/linux-arch/PKGBUILD
docs/packaging/linux-arch/README.md
docs/packaging/linux-centos/README.md
docs/packaging/linux-debian/README.md
docs/packaging/linux-fedora/README.md
docs/packaging/linux-gentoo/Manifest
docs/packaging/linux-gentoo/README.md
docs/packaging/linux-gentoo/httpie-2.5.0.ebuild
docs/packaging/linux-gentoo/metadata.xml
docs/packaging/linux-void/README.md
docs/packaging/linux-void/template
docs/packaging/mac-ports/Portfile
docs/packaging/mac-ports/README.md
docs/packaging/snapcraft/README.md
docs/packaging/spack/README.md
docs/packaging/spack/package.py
docs/packaging/windows-chocolatey/README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-06: Fix looked path for workflow testing packages
.github/workflows/test-package-linux-snap.yml
.github/workflows/test-package-mac-brew.yml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-06: Add install/update instructions database (#1160)
.github/workflows/code-style.yml
.github/workflows/coverage.yml
.github/workflows/docs-check-markdown.yml
.github/workflows/docs-deploy.yml
.github/workflows/docs-update-install.yml
.github/workflows/release.yml
.github/workflows/test-package-linux-snap.yml
.github/workflows/test-package-mac-brew.yml
.github/workflows/tests.yml
Makefile
docs/README.md
docs/installation/README.md
docs/installation/generate.py
docs/installation/installation.jinja2
docs/installation/methods.yml
docs/markdownlint.rb
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-05: Add `make install-reqs` to install packages without creating env
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-05: Cover on Python 3.10
.github/workflows/coverage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-05: Add self to paths; same paths for PR and push
.github/workflows/tests.yml

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-05: Test on Python 3.10
.github/workflows/tests.yml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-05: Fix docs formatting
Makefile
docs/README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-10-05: Mention Snapcraft for unstable version installation
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-03: Update README.md
README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-03: Remove redundant/inconsistent article
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-03: Expand HTTP method docs
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-02: Update setup.py
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-10-02: Update utils.py
httpie/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-30: Update config.json
docs/config.json

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-30: master/latest docs differ since --response-as
docs/config.json

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-29: Improve handling of prettified responses without correct content-type encoding (#1110)
CHANGELOG.md
docs/README.md
httpie/cli/definition.py
httpie/codec.py
httpie/models.py
httpie/output/formatters/xml.py
httpie/output/streams.py
setup.py
tests/test_errors.py
tests/test_unicode.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-28: Use PYthon 3 documentation
httpie/sessions.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-28: Use httpie.io/docs everywhere
httpie/cli/argparser.py
httpie/cli/definition.py
httpie/sessions.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-27: Sort available style choices (#1166)
httpie/cli/definition.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-27: Allow to overwrite the response Content-Type from options (#1134)
CHANGELOG.md
docs/README.md
httpie/cli/argparser.py
httpie/cli/constants.py
httpie/cli/definition.py
httpie/output/processing.py
httpie/output/streams.py
httpie/output/utils.py
tests/test_output.py
tests/test_xml.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-24: Remove trailing comma in test
tests/test_binary.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-23: Sort changelog
CHANGELOG.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-23: Include plugin info in `--debug` output (#1165)
CHANGELOG.md
docs/README.md
httpie/core.py
httpie/plugins/manager.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-23: Mention XML when explaining formatting
docs/README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-23: Add FreeBSD installation instructions
docs/README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-23: Add workflow to test with pyOpenSSL active (#1164)
.github/workflows/tests.yml
setup.py
tests/conftest.py
tests/test_ssl.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-21: Fix duplicate keys preservation of JSON data (#1163)
CHANGELOG.md
httpie/cli/requestitems.py
httpie/output/utils.py
httpie/utils.py
tests/fixtures/__init__.py
tests/fixtures/test_with_dupe_keys.json
tests/test_cli.py
tests/test_json.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-21: Improve JSON output when there is leading data before the actual JSON body (#1130)
CHANGELOG.md
httpie/output/formatters/colors.py
httpie/output/formatters/json.py
httpie/output/lexers/__init__.py
httpie/output/lexers/http.py
httpie/output/lexers/json.py
httpie/output/utils.py
tests/test_json.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-21: Bump the version to 2.6.0.dev0 (#1162)
CHANGELOG.md
docs/README.md
httpie/__init__.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-20: Expand the pytest configuration (#1161)
Makefile
setup.cfg

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-15: [snap] Improve OS integration (#1157)
snapcraft.yaml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-15: Use HTTPie for the documentation build request (#1150)
.github/workflows/update-documentation.yml

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-14: Add a blog post link
CHANGELOG.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-13: Remove some horizontal lines in the bug report
.github/ISSUE_TEMPLATE/bug_report.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-13: Reverse results in bug report temlpate
.github/ISSUE_TEMPLATE/bug_report.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-11: Update README.md
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-10: Update config.json
docs/config.json

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-10: Update update-documentation.yml
.github/workflows/update-documentation.yml

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-10: Update update-documentation.yml
.github/workflows/update-documentation.yml

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-10: Update and rename documentations.yml to check-markdown.yml
.github/workflows/check-markdown.yml

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-10: Create config.json
docs/config.json

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-10: Update README.md
README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-10: Update README.md
README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-10: [snap] Comment out the problematic interface
snapcraft.yaml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-10: [snap] Remove personal-files interface
.github/workflows/packaging-linux-snap.yml
.github/workflows/packaging-mac-brew.yml
snapcraft.yaml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-09: Complete CentOS installation instructions
docs/README.md

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-09: Add the release workflow
.github/workflows/release.yml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-09: Add a workflow to check documentations (#1151)
.github/ISSUE_TEMPLATE/bug_report.md
.github/ISSUE_TEMPLATE/feature_request.md
.github/workflows/documentations.yml
CODE_OF_CONDUCT.md
CONTRIBUTING.md
Makefile
README.md
docs/README.md
docs/linter/mdl-styles.rb
setup.py
tests/test_docs.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-08: Split the monolithic workflow into specific ones (#1149)
.github/workflows/build.yml
.github/workflows/code-style.yml
.github/workflows/coverage.yml
.github/workflows/packaging-mac-check-formula.yml
.github/workflows/tests.yml
.github/workflows/update-documentation.yml
Makefile

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-08: Trigger official documentation build when documentation is updated here
.github/workflows/update_documentation.yml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-08: Update brew formula to 2.5.0 (#1144)
.github/workflows/packaging_mac_check_formula.yml
Makefile
extras/brew-deps.py
extras/httpie.rb

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-08: Add Alpine Linux installation instructions
docs/README.md

## Omer Akram (om26er@gmail.com) on 2021-09-07: Use lzo compression for snap (#1146)
snapcraft.yaml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-07-02: Add the Snap build file for general Linux packaging
docs/README.md
snapcraft.yaml

## Miro Hron─ìok (miro@hroncok.cz) on 2021-09-07: Packit: Get the current Fedora Rawhide specfile
.packit.yaml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-06: v2.5.0 (#1140)
CHANGELOG.md
docs/README.md
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-06: Cleanup
README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-06: Cleanup
README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-06: Cleanup
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-06: Cleanup
README.md
docs/README.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-06: Readme tweaks (#1141)
README.md
docs/README.md
docs/httpie-animation.gif
docs/httpie-logo.svg
httpie.png

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-06: Switch from reStructuredText to Markdown and add `docs/` (#1139)
AUTHORS.md
AUTHORS.rst
CHANGELOG.md
CHANGELOG.rst
CODE_OF_CONDUCT.md
CONTRIBUTING.md
CONTRIBUTING.rst
MANIFEST.in
Makefile
README.md
README.rst
docs/README.md
setup.py
tests/README.md
tests/README.rst
tests/test_docs.py

## a1346054 (36859588+a1346054@users.noreply.github.com) on 2021-09-03: Spelling and bash completion fixes (#1137)
.github/ISSUE_TEMPLATE/bug_report.md
CHANGELOG.rst
CONTRIBUTING.rst
README.rst
extras/httpie-completion.bash

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-02: Tiny clean-up in `program()` (#1135)
httpie/core.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-09-02: Update CHANGELOG.rst
CHANGELOG.rst

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-01: Move example URL in a global variable for XML tests
tests/test_xml.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-01: Move example URL in a global variable for tests
tests/test_stream.py
tests/utils/__init__.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-09-01: Fix XML formatter tests
httpie/output/formatters/xml.py
tests/fixtures/xmldata/valid/dtd_formatted.xml
tests/fixtures/xmldata/valid/simple-ns_formatted.xml
tests/fixtures/xmldata/valid/simple_formatted.xml
tests/fixtures/xmldata/xhtml/xhtml_formatted.xml
tests/fixtures/xmldata/xhtml/xhtml_formatted_python_less_than_3.8.xml
tests/test_output.py
tests/test_xml.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-08-31: Change default XML indent to 2 spaces
README.rst
httpie/cli/constants.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-08-31: Added support for XML formatting (#1129)
AUTHORS.rst
CHANGELOG.rst
README.rst
extras/brew-deps.py
httpie/cli/constants.py
httpie/output/formatters/xml.py
httpie/plugins/registry.py
setup.py
tests/fixtures/__init__.py
tests/fixtures/xmldata/invalid/cyclic.xml
tests/fixtures/xmldata/invalid/external.xml
tests/fixtures/xmldata/invalid/external_file.xml
tests/fixtures/xmldata/invalid/not-xml.xml
tests/fixtures/xmldata/invalid/quadratic.xml
tests/fixtures/xmldata/invalid/xalan_exec.xsl
tests/fixtures/xmldata/invalid/xalan_write.xsl
tests/fixtures/xmldata/invalid/xmlbomb.xml
tests/fixtures/xmldata/invalid/xmlbomb2.xml
tests/fixtures/xmldata/valid/dtd_formatted.xml
tests/fixtures/xmldata/valid/dtd_raw.xml
tests/fixtures/xmldata/valid/simple-ns_formatted.xml
tests/fixtures/xmldata/valid/simple-ns_raw.xml
tests/fixtures/xmldata/valid/simple-standalone-no_formatted.xml
tests/fixtures/xmldata/valid/simple-standalone-no_raw.xml
tests/fixtures/xmldata/valid/simple-standalone-yes_formatted.xml
tests/fixtures/xmldata/valid/simple-standalone-yes_raw.xml
tests/fixtures/xmldata/valid/simple_formatted.xml
tests/fixtures/xmldata/valid/simple_raw.xml
tests/fixtures/xmldata/xhtml/xhtml_formatted.xml
tests/fixtures/xmldata/xhtml/xhtml_formatted_python_less_than_3.8.xml
tests/fixtures/xmldata/xhtml/xhtml_raw.xml
tests/test_output.py
tests/test_xml.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-08-24: Tweak format options docs
README.rst

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-08-24: Add the formatting options section in the docs (#1131)
README.rst

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-08-17: Fix missing links in the changelog
CHANGELOG.rst

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-08-16: Fix handling of session files with `Cookie:` followed by other headers (#1127)
CHANGELOG.rst
httpie/sessions.py
tests/test_sessions.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-08-06: Remove unused code in `BasicConfig` (#1123)
httpie/config.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-08-06: Rework `__main__.py` to follow best practices (#1124)
httpie/__main__.py
tests/test_httpie.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-08-06: CI: Run tests on Python 3.10 RC1 (#1121)
.github/dependabot.yml
.github/workflows/build.yml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-08-06: Simplify `get_content_type()` (#1125)
httpie/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-08-05: Use `UTF8` constant in `FORM_CONTENT_TYPE` as well
httpie/client.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-08-05: Uniformize UTF-8 naming (#1115)
httpie/cli/argparser.py
httpie/cli/requestitems.py
httpie/client.py
httpie/config.py
httpie/constants.py
httpie/context.py
httpie/models.py
httpie/output/streams.py
httpie/plugins/builtin.py
httpie/sessions.py
tests/fixtures/__init__.py
tests/test_cli.py
tests/test_config.py
tests/test_docs.py
tests/test_downloads.py
tests/test_httpie.py
tests/test_output.py
tests/test_sessions.py
tests/test_unicode.py
tests/test_uploads.py
tests/utils/__init__.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-08-05: Refine abstract methods and properties (#1118)
httpie/models.py
httpie/output/streams.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-08-05: Use builtin `open()` in `setup.py` (#1120)
setup.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-08-05: Add converter plugin streaming tests (#1117)
setup.py
tests/test_output.py
tests/test_stream.py
tests/test_unicode.py

## Miro Hron─ìok (miro@hroncok.cz) on 2021-08-04: Packit: Enable the Koji repsitory in Copr (#1119)
.packit.yaml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-07-29: --download: Use `time.monotonic()` and rework code to prevent `ZeroDivisionError` specific handling (#1113)
httpie/downloads.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-07-26: Minor clean-up (#1112)
httpie/context.py
httpie/downloads.py
httpie/output/writer.py
tests/test_sessions.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-07-26: Add more download tests (#1114)
tests/test_downloads.py

## Anton Emelyanov (ainzzorl+github@pm.me) on 2021-07-20: Simplify spinner_pos calculation a little (#1111)
httpie/downloads.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-07-16: Revert "Use `http` in the 'hello world' example to be consitent (#1109)"
README.rst

## henryhu712 (henryhu712@gmail.com) on 2021-07-15: Use `http` in the 'hello world' example to be consitent (#1109)
README.rst

## Ilya Sukhanov (ilya@sukhanov.net) on 2021-07-06: Add internal support for file-like object responses to improve adapter plugin support (#1094)
CHANGELOG.rst
httpie/client.py
httpie/models.py
httpie/utils.py
tests/test_cookie.py
tests/test_sessions.py
tests/test_transport_plugin.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-07-02: Update Chocolatey command in the docs
README.rst

## Marcel St├╢r (marcelstoer@users.noreply.github.com) on 2021-07-02: Use `echo -n` in the docs (#1102)
README.rst

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-07-01: Normalize the version (#1101)
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-06-28: Remove snap installation method until package name fixed
README.rst

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-06-28: Mention `snap install http` in the docs (#1097)
README.rst

## nixbytes (real8686@gmail.com) on 2021-06-28: Simplify return statements in client.py (#1096)
httpie/client.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-06-26: Skip tests that randomly fail on Windows in CI
tests/test_redirects.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-06-26: Mention `choco install httpie` in the docs
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2021-06-15: Add `--follow` test for HTTP 308
tests/test_redirects.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-06-15: Add `--follow --verbose` test for HTTP 308
tests/test_redirects.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-06-15: Mention `308 Permanent Redirect`
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2021-06-15: Final touches for #1088 (#1091)
CHANGELOG.rst
README.rst
tests/fixtures/.editorconfig
tests/fixtures/test.json
tests/fixtures/test.txt
tests/test_redirects.py
tests/test_tokens.py
tests/utils/matching/__init__.py
tests/utils/matching/parsing.py
tests/utils/matching/tokens.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-06-15: Fix printing redirected prepared request in verbose mode (#1088)
httpie/core.py
tests/test_redirects.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-06-11: CI: Do not fail fast to have a real view of potential failures (#1090)
.github/workflows/build.yml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-06-11: Use a more modern approach to run tests (#1089)
.github/workflows/build.yml
CONTRIBUTING.rst
Makefile
requirements-dev.txt
setup.py

## Miro Hron─ìok (miro@hroncok.cz) on 2021-06-09: Add a Packit configuration for Fedora packaging (#1086)
.gitignore
.packit.yaml

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-06-09: Prevent installation of test files (#1087)
setup.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-06-09: Add a reproduction test case for #1082 (#1085)
tests/test_redirects.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-06-02: Switch from pycodestyle to flake8 for code style checks (#1083)
.github/workflows/build.yml
CONTRIBUTING.rst
Makefile
requirements-dev.txt
setup.cfg
tests/utils/__init__.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-06-01: Fix several issues found with flake8 (#1081)
httpie/cli/definition.py
httpie/config.py
setup.cfg
setup.py
tests/test_docs.py
tests/test_httpie.py
tests/test_output.py
tests/test_sessions.py
tests/test_windows.py
tests/utils/matching/test_matching.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-05-31: Review OSError exceptions handling (#1080)
httpie/cli/argparser.py
httpie/cli/argtypes.py
httpie/cli/requestitems.py
httpie/config.py
httpie/downloads.py
httpie/output/writer.py
tests/test_ssl.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-05-29: Minor clean-up (#1078)
httpie/config.py
httpie/plugins/__init__.py
tests/conftest.py
tests/test_config.py
tests/test_output.py
tests/test_sessions.py
tests/test_uploads.py
tests/test_windows.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-05-28: Fix --style colors list help indentation (#1077)
httpie/cli/definition.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-05-27: Remove Python 3.10 build
.github/workflows/build.yml

## Jakub Roztocil (jakub@roztocil.co) on 2021-05-27: Add Python 3.10 build
.github/workflows/build.yml

## Jannik Vieten (me@exploide.net) on 2021-05-27: updated fish shell completions (#1076)
extras/httpie-completion.fish

## Miro Hron─ìok (miro@hroncok.cz) on 2021-05-27: Adapt doctest of tests.utils.http to work on Python 3.10 as well (#1075)
tests/utils/__init__.py

## Miro Hron─ìok (miro@hroncok.cz) on 2021-05-27: Skip http://pie.dev tests when offline (#1072)
tests/conftest.py
tests/test_tokens.py
tests/test_uploads.py
tests/utils/__init__.py

## Miro Hron─ìok (miro@hroncok.cz) on 2021-05-27: Declare a [test] extra with test dependencies (#1074)
setup.py

## Miro Hron─ìok (miro@hroncok.cz) on 2021-05-27: Remove an useless shebang form non-executable file (#1073)
httpie/__main__.py

## Miro Hron─ìok (miro@hroncok.cz) on 2021-05-27: pytest: Add hidden files to norecursedirs (#1071)
setup.cfg

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-05-27: Polish Python 2 removal (#1070)
httpie/downloads.py
httpie/models.py
httpie/output/formatters/colors.py
httpie/output/formatters/json.py
httpie/output/writer.py
httpie/utils.py
tests/test_sessions.py
tests/test_unicode.py
tests/utils/__init__.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-05-26: Modernize the code base with f-strings in tests (#1069)
tests/test_auth_plugins.py
tests/test_cli.py
tests/test_httpie.py
tests/test_output.py
tests/test_regressions.py
tests/test_sessions.py
tests/test_ssl.py
tests/test_unicode.py
tests/utils/__init__.py
tests/utils/matching/test_matching.py

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-05-25: Modernize the code base with f-strings (#1068)
httpie/cli/argparser.py
httpie/cli/definition.py
httpie/cli/requestitems.py
httpie/core.py
httpie/downloads.py
httpie/models.py
httpie/output/formatters/colors.py
httpie/plugins/builtin.py
httpie/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-05-24: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2021-05-24: README
README.rst

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2021-05-24: Add --raw to allow specifying the raw request body as an alternative to stdin (#1062)
CHANGELOG.rst
README.rst
extras/httpie-completion.bash
extras/httpie-completion.fish
httpie/cli/argparser.py
httpie/cli/definition.py
tests/test_compress.py
tests/test_defaults.py
tests/test_httpie.py
tests/test_offline.py
tests/test_output.py
tests/test_unicode.py

## Micka├½l Schoentgen (mschoentgen@nuxeo.com) on 2021-05-05: Prefer usage of "python -m pip" instead of "pip" (#1059)
CHANGELOG.rst
CONTRIBUTING.rst
README.rst

## Micka├½l Schoentgen (mschoentgen@nuxeo.com) on 2021-05-05: Use relative imports (#1057)
AUTHORS.rst
httpie/__main__.py
httpie/cli/argparser.py
httpie/cli/argtypes.py
httpie/cli/definition.py
httpie/cli/requestitems.py
httpie/client.py
httpie/config.py
httpie/context.py
httpie/core.py
httpie/downloads.py
httpie/output/formatters/colors.py
httpie/output/formatters/headers.py
httpie/output/formatters/json.py
httpie/output/processing.py
httpie/output/streams.py
httpie/output/writer.py
httpie/plugins/__init__.py
httpie/plugins/builtin.py
httpie/plugins/manager.py
httpie/plugins/registry.py
httpie/sessions.py
httpie/uploads.py
tests/__init__.py
tests/test_auth.py
tests/test_auth_plugins.py
tests/test_binary.py
tests/test_cli.py
tests/test_compress.py
tests/test_config.py
tests/test_defaults.py
tests/test_docs.py
tests/test_downloads.py
tests/test_errors.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_offline.py
tests/test_output.py
tests/test_redirects.py
tests/test_regressions.py
tests/test_sessions.py
tests/test_ssl.py
tests/test_stream.py
tests/test_tokens.py
tests/test_unicode.py
tests/test_uploads.py
tests/test_windows.py
tests/utils/matching/__init__.py
tests/utils/matching/parsing.py
tests/utils/matching/test_matching.py

## Micka├½l Schoentgen (mschoentgen@nuxeo.com) on 2021-05-03: Prefer usage of pytest rather than py.test (#1058)
CONTRIBUTING.rst
Makefile

## Micka├½l Schoentgen (mschoentgen@nuxeo.com) on 2021-04-30: Replace usage of mock with unittest.mock (#1054)
requirements-dev.txt
setup.py
tests/test_auth.py
tests/test_auth_plugins.py
tests/test_downloads.py
tests/test_errors.py
tests/test_exit_status.py
tests/test_output.py
tests/test_sessions.py

## Jan Verbeek (jan.verbeek@posteo.nl) on 2021-04-15: Fail gracefully if multiple request data files are supplied (#1042)
httpie/cli/argparser.py
tests/test_uploads.py

## Miro Hron─ìok (miro@hroncok.cz) on 2021-03-30: Explicitly require setuptools, httpie/plugins/manager.py imports pkg_resources (#1049)
setup.py

## Almad (almad@apible.io) on 2021-02-24: Warn against non-ascii in setup.cfg (#1041)
setup.cfg

## Almad (almad@apible.io) on 2021-02-24: Replace typography quotes (#1040)
setup.cfg

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-23: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-23: Typo
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-18: Tweaks
.github/ISSUE_TEMPLATE/feature_request.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-18: Tweaks
.github/ISSUE_TEMPLATE/bug_report.md
.github/ISSUE_TEMPLATE/feature_request.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-18: Spacing
.github/ISSUE_TEMPLATE/bug_report.md
.github/ISSUE_TEMPLATE/feature_request.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-18: Issue templates tweaks II
.github/ISSUE_TEMPLATE/bug_report.md
.github/ISSUE_TEMPLATE/feature_request.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-18: Issue templates tweaks
.github/ISSUE_TEMPLATE/bug_report.md
.github/ISSUE_TEMPLATE/feature_request.md
.github/ISSUE_TEMPLATE/other.md

## Elena Lape (elapinskaite@gmail.com) on 2021-02-18: Issue templates (#1031)
.github/ISSUE_TEMPLATE/bug_report.md
.github/ISSUE_TEMPLATE/feature_request.md
.github/ISSUE_TEMPLATE/other.md

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-14: Formatting
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-14: CHANGELOG #1032
CHANGELOG.rst

## Jan Verbeek (jan.verbeek@posteo.nl) on 2021-02-14: Correctly handle single-byte Content-Range (#1032)
httpie/downloads.py
tests/test_downloads.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-06: 2.5.0-dev
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-06: 2021
LICENSE

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-06: Tests
tests/test_tokens.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-06: Update brew formula to 2.4.0
extras/brew-deps.py
extras/httpie.rb

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-06: Typo
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-06: 2.4.0
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-06: Update upload command
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-06: Fix README formatting
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-06: Changelog entry for cookie expiration based on `Set-Cookie: max-age=<n>`
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-06: Refactoring
httpie/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-02-06: Add more output matching tests
tests/test_tokens.py

## Denis Belavin (41421345+LuckyDenis@users.noreply.github.com) on 2021-02-06: Add support for max-age=0 cookie expiry (#1029)
AUTHORS.rst
httpie/utils.py
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-01-31: Show --check-status warning with --quiet as well. (#1026)
CHANGELOG.rst
README.rst
httpie/core.py
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.co) on 2021-01-30: Fix incorrect separators and introduce `assert_output_matches()` (close #1027)
CHANGELOG.rst
httpie/core.py
httpie/output/writer.py
setup.cfg
tests/test_regressions.py
tests/test_tokens.py
tests/utils/__init__.py
tests/utils/matching/__init__.py
tests/utils/matching/parsing.py
tests/utils/matching/test_matching.py

## freddii (freddii@users.noreply.github.com) on 2021-01-21: fixed typo (#1024)
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2021-01-13: Update chat icon
README.rst

## Adam (adam@lesniak.pl) on 2021-01-13: Add Linux Solus install to README (#1018)
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2021-01-13: Update changelog
CHANGELOG.rst

## Gian Ortiz (brksgian@gmail.com) on 2021-01-13: Decode headers using utf-8 only if they are not str (#1020)
httpie/sessions.py
tests/test_sessions.py

## Elena Lape (elapinskaite@gmail.com) on 2021-01-12: Add HTTPie Discord link to README (#1016)
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-12-24: Switch from httpbin.org to pie.dev
CHANGELOG.rst
README.rst
tests/test_regressions.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-12-23: Update URLs
AUTHORS.rst
CHANGELOG.rst
CONTRIBUTING.rst
MANIFEST.in
httpie/cli/definition.py
httpie/client.py
httpie/downloads.py
httpie/plugins/builtin.py
tests/README.rst
tests/test_auth.py
tests/test_defaults.py
tests/test_httpie.py
tests/test_output.py
tests/test_regressions.py
tests/test_sessions.py
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-12-22: Add a test to reproduce #1006
tests/test_regressions.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-12-21: Update `--stream` example comment
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-12-21: Fix `--stream` example II
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-12-21: Fix `--stream` example
README.rst

## Shubhendra Singh Chauhan (withshubh@gmail.com) on 2020-12-21: Cleanup (#993)
httpie/cli/constants.py
httpie/cli/requestitems.py
httpie/core.py
setup.py
tests/test_downloads.py
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-12-21: Clarify
README.rst

## Kevin Velghe (kevin@paretje.be) on 2020-12-21: Fix documentation on file upload (#1000)
README.rst

## Dustin Rodrigues (dust.rod@gmail.com) on 2020-12-21: Test on Python 3.9 (#986)
.github/workflows/build.yml

## xcodz-dot (71920621+xcodz-dot@users.noreply.github.com) on 2020-12-21: python -m pip (#1005)
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-12-19: Update setup.py
setup.py

## Almad (almad@apible.io) on 2020-12-18: Remove funding request
.github/FUNDING.yml

## Jakub Roztocil (jakub@roztocil.co) on 2020-10-29: Simplify Hello World
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-10-29: Simplify Hello World
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-10-25: Update brew instructions for dev
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-10-25: Update homebrew
README.rst
extras/httpie.rb

## Jakub Roztocil (jakub@roztocil.co) on 2020-10-25: 2.4.0-dev
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-10-25: v2.3.0
CHANGELOG.rst
Makefile
README.rst
httpie/__init__.py
httpie/core.py
setup.py
tests/test_uploads.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-10-03: Update setup.py
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-10-03: New Twitter handle ΓÇö @httpie
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-29: Fix table formatting
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-28: Cleanup
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-28: Cleanup
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-28: Fix `--offline --chunked`, add more tests
httpie/client.py
tests/test_httpie.py
tests/test_offline.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-28: Fix `--offline --multipart`, add more tests
httpie/client.py
httpie/core.py
httpie/uploads.py
tests/test_httpie.py
tests/test_uploads.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-28: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-28: Fix fixture encoding on Windows
tests/fixtures/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-28: PEP8
httpie/core.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-28: Merge branch 'feature/uploads2020'
## Jakub Roztocil (jakub@roztocil.co) on 2020-09-28: Add support for streamed uploads, --chunked, finish --multipart, etc.
CHANGELOG.rst
README.rst
httpie/cli/argparser.py
httpie/cli/argtypes.py
httpie/cli/constants.py
httpie/cli/definition.py
httpie/cli/dicts.py
httpie/cli/requestitems.py
httpie/client.py
httpie/core.py
httpie/output/formatters/colors.py
httpie/output/streams.py
httpie/output/writer.py
httpie/uploads.py
tests/fixtures/__init__.py
tests/test_cli.py
tests/test_compress.py
tests/test_defaults.py
tests/test_httpie.py
tests/test_stream.py
tests/test_uploads.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-25: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-25: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-25: Merge branch 'master' into feature/uploads2020
## Jakub Roztocil (jakub@roztocil.co) on 2020-09-25: Request content type
README.rst
httpie/cli/argparser.py
httpie/cli/constants.py
httpie/cli/definition.py
httpie/client.py
httpie/output/streams.py
httpie/ssl.py
httpie/uploads.py
tests/test_uploads.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-25: WIP
httpie/cli/argparser.py
httpie/cli/definition.py
httpie/client.py
httpie/core.py
httpie/output/streams.py
httpie/output/writer.py
httpie/uploads.py
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-20: CHANGELOG
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-09-20: Gracefully ignore cookie expiry dates in invalid format
httpie/utils.py
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-19: pep8
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-19: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-19: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-19: Cleanup
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-19: Add `--multipart` and `--boundary`
CHANGELOG.rst
README.rst
httpie/cli/argparser.py
httpie/cli/definition.py
httpie/client.py
httpie/uploads.py
tests/test_uploads.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-17: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-17: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-17: Update __init__.py
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-17: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-15: pep8
httpie/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-15: Add support for multipart upload streaming
CHANGELOG.rst
README.rst
extras/brew-deps.py
httpie/cli/requestitems.py
httpie/client.py
httpie/output/streams.py
httpie/uploads.py
httpie/utils.py
setup.py
tests/test_uploads.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-15: Syntax
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-15: Add a `--quiet` example
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-15: Finish `--quiet`
.github/FUNDING.yml
CHANGELOG.rst
README.rst
httpie/context.py
tests/test_downloads.py
tests/test_output.py

## Nicolas Beltran (nb2838@columbia.edu) on 2020-08-13: Added additional tests to verify downloads work properly with quiet flag
tests/test_downloads.py
tests/test_output.py

## Nicolas Beltran (nb2838@columbia.edu) on 2020-08-11: fixed issues related to downloading and using quiet at the same time
README.rst
httpie/cli/argparser.py
httpie/cli/definition.py

## Nicolas Beltran (nb2838@columbia.edu) on 2020-07-14: Additional Aesthetic changes
httpie/cli/argparser.py
httpie/context.py

## Nicolas Beltran (nb2838@columbia.edu) on 2020-07-14: Aesthetic changes
httpie/context.py
tests/test_downloads.py
tests/test_output.py
tests/utils.py

## Nicolas Beltran (nb2838@columbia.edu) on 2020-07-14: Added additional tests for  flag and better documentation
README.rst
tests/test_downloads.py
tests/test_output.py

## Nicolas Beltran (nb2838@columbia.edu) on 2020-07-14: Solved issue pertaining to downloads and added additional testing functionality for devnull
httpie/context.py
tests/utils.py

## Nicolas Beltran (nb2838@columbia.edu) on 2020-07-14: Added changes suggested in the PR review
CHANGELOG.rst
httpie/cli/argparser.py

## Nicolas Beltran (nb2838@columbia.edu) on 2020-06-27: Added a documentation entry and modified CHANGELOG
CHANGELOG.rst
README.rst

## Nicolas Beltran (nb2838@columbia.edu) on 2020-06-27: Added tests for --quiet flag
httpie/cli/argparser.py
httpie/context.py
tests/test_downloads.py
tests/test_output.py

## Nicolas Beltran (nb2838@columbia.edu) on 2020-06-26: Added a quiet functionality
httpie/cli/argparser.py
httpie/cli/definition.py
httpie/context.py

## Nguyß╗àn Hß╗ông Qu├ón (ng.hong.quan@gmail.com) on 2020-08-14: Introduce CurliPie to convert from cURL to HTTPie (#843)
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-08-06: Update build.yml
.github/workflows/build.yml

## matthewhughes934 (34972397+matthewhughes934@users.noreply.github.com) on 2020-08-06: Quieten ssl tests (#952)
tests/client_certs/client.crt
tests/client_certs/client.key
tests/client_certs/client.pem
tests/test_ssl.py

## Syed (GotoCode@users.noreply.github.com) on 2020-07-16: Fix minor typos in the README and CONTRIBUTING docs (#956)
CONTRIBUTING.rst
README.rst

## Katherine Bancroft (katherine.bancroft@gmail.com) on 2020-07-10: Add test to test auth plugin reused in session (#938)
README.rst
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-07-07: Install setuptools & wheel in CI II.
.github/workflows/build.yml

## Jakub Roztocil (jakub@roztocil.co) on 2020-07-07: Install setuptools & wheel in CI
.github/workflows/build.yml
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-07-07: Add wheel to tests_require
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-07-07: Split session JSON serialization and writing to file
httpie/config.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-07-07: Update CONTRIBUTING.rst
CONTRIBUTING.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-26: Reorganize and expand CONTRIBUTING.rst
CONTRIBUTING.rst

## Shageldi Ovezov (44060682+ovezovs@users.noreply.github.com) on 2020-06-26: Add Windows setup instructions (#941)
CONTRIBUTING.rst

## Shageldi Ovezov (44060682+ovezovs@users.noreply.github.com) on 2020-06-26: Remove tox (#944)
.gitignore
CHANGELOG.rst
CONTRIBUTING.rst
Makefile
requirements-dev.txt
setup.cfg
tox.ini

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-25: Cleanup inline to-dos
Makefile
httpie/cli/constants.py
httpie/cli/definition.py
tests/test_docs.py
tests/test_httpie.py
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-19: Fixed `test_ciphers_none_can_be_selected` on OpenBSD
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-19: Update Brew formula for v2.2.0
extras/httpie.rb

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-19: Fix install_requires
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-19: Install requests[socks] by default for out of the box SOCKS support
CHANGELOG.rst
README.rst
setup.py

## Andrew (sheer.luck.andrew@gmail.com) on 2020-06-19: Update README.rst (#737)
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-18: CHANGELOG + README
CHANGELOG.rst
README.rst

## Katherine Bancroft (katherine.bancroft@gmail.com) on 2020-06-18: Combine cookies from original request and session file
README.rst
httpie/sessions.py
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-18: v2.3.0-dev
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-18: v2.2.0
CHANGELOG.rst
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-18: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-16: Clarify config docs
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-16: Cleanup
CHANGELOG.rst
httpie/cli/definition.py
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-16: Add --sorted
CHANGELOG.rst
httpie/cli/constants.py
httpie/cli/definition.py
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-16: Cleanup
httpie/cli/definition.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-16: Fix default value
httpie/cli/argparser.py
httpie/cli/definition.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-16: Added --unsorted
CHANGELOG.rst
httpie/cli/argparser.py
httpie/cli/argtypes.py
httpie/cli/constants.py
httpie/cli/definition.py
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-16: Added netrc support for auth plugins.
CHANGELOG.rst
httpie/cli/argparser.py
httpie/plugins/base.py
httpie/plugins/builtin.py
tests/test_auth.py

## Nicolas Beltran (nb2838@columbia.edu) on 2020-06-09: Added a test that verifies .netrc is honored when only --auth-type is passed
tests/test_auth.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-15: Update CHANGELOG.rst
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-15: Cleanup
httpie/client.py
httpie/sessions.py
httpie/utils.py
tests/test_sessions.py

## Eyitayo Ogunbiyi (eyitayoogunbiyi@gmail.com) on 2020-06-15: Remove expired cookies (#929)
httpie/client.py
httpie/sessions.py
httpie/utils.py
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-06-08: Update CHANGELOG
CHANGELOG.rst
httpie/cli/definition.py

## Carlo Sciolla (skuro@skuro.tk) on 2020-06-08: Custom file upload MIME type (#927)
CHANGELOG.rst
README.rst
httpie/cli/constants.py
httpie/cli/definition.py
httpie/cli/requestitems.py
tests/test_uploads.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-28: Add stable docs link icon
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-28: Use `:` instead of `=` in ``--format-options`
README.rst
httpie/cli/argtypes.py
httpie/cli/constants.py
httpie/cli/definition.py
tests/test_output.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-27: Improve --format-options error messages
httpie/cli/argtypes.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-27: pep8
httpie/cli/argtypes.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-27: Add --format-options to allow disabling sorting, etc.
CHANGELOG.rst
README.rst
httpie/cli/argtypes.py
httpie/cli/constants.py
httpie/cli/definition.py
httpie/output/formatters/headers.py
httpie/output/formatters/json.py
httpie/output/writer.py
httpie/plugins/base.py
setup.cfg
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-26: Update CHANGELOG
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-26: Improve plugin API docs
httpie/plugins/base.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-26: Refactor built-in plugin registry to avoid circular imports
httpie/cli/argparser.py
httpie/cli/definition.py
httpie/client.py
httpie/core.py
httpie/output/processing.py
httpie/plugins/__init__.py
httpie/plugins/registry.py
httpie/sessions.py
tests/test_auth_plugins.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-23: Cleanup
httpie/client.py
httpie/ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-23: Pass cert_reqs to context
httpie/client.py
httpie/ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-23: Fix SSL context
httpie/ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-23: Add examples
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-23: Add examples
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-23: Add docs for the `https` command alias
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-23: Add support for --ciphers (#870)
CHANGELOG.rst
README.rst
httpie/cli/constants.py
httpie/cli/definition.py
httpie/client.py
httpie/ssl.py
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-23: Str env vars
tests/test_config.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-23: Cleanup & refactor XDG_CONFIG_HOME support
httpie/config.py
tests/test_config.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-22: Update CHANGELOG.rst
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-21: Fix issue links
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-21: Added changelog entry for $XDG_CONFIG_HOME support
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-21: Update ~/.httpie references to ~/.config/httpie
README.rst

## Ash Holland (ash@sorrel.sh) on 2020-05-21: Support (part of) the XDG Base Directory Specification (#920)
README.rst
httpie/config.py
tests/test_config.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-05-13: Update FUNDING.yml
.github/FUNDING.yml

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-24: Update README.rst
README.rst

## Jakob Krigovsky (jakob@krigovsky.com) on 2020-04-20: Fix typo (#898)
.gitignore

## Jakob Krigovsky (jakob@krigovsky.com) on 2020-04-20: Fix spelling of ΓÇ£GitHubΓÇ¥ (#899)
CHANGELOG.rst
CONTRIBUTING.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-18: Update CHANGELOG.rst
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-18: Fix brew formula
extras/httpie.rb

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-18: Update brew formula
extras/httpie.rb

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-18: 2.2.0-dev
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-18: 2.1.0
CHANGELOG.rst
README.rst
httpie/__init__.py
setup.cfg
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-13: Change default JSON `Accept` to `application/json, */*;q=0.5`
tests/test_defaults.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-06: accept wip
tests/test_defaults.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-16: Add an `--offline` example
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-16: Ignore `--download` with `--offline`
httpie/cli/argparser.py
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-16: Add `--path-as-is` docs
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-16: Add `--offline` mode docs
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-16: Add tests for `--offline`
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-15: Readme WIP
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-15: Fix 'Too many redirects' error message formatting
httpie/core.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-13: Change default JSON `Accept` to `application/json, */*;q=0.5`
CHANGELOG.rst
README.rst
httpie/client.py
tests/test_defaults.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-13: Add `--path-as-is`
CHANGELOG.rst
httpie/cli/definition.py
httpie/client.py
tests/test_httpie.py

## Mio (inory009@gmail.com) on 2020-04-14: Removed duplicate type annotation. (#888)
httpie/downloads.py

## Doug Beney (git__0hub@dougie.io) on 2020-04-13: apt (#890)
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-13: Remove unused imports
httpie/context.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-04-13: Build on PRs as well
.github/workflows/build.yml

## Jakub Roztocil (jakub@roztocil.co) on 2020-03-27: Update examples
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-03-20: Update --download doc
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-03-22: 2020
LICENSE

## Jakub Roztocil (jakub@roztocil.co) on 2020-01-23: Actually fixed `--form` file upload w/ redirected `stdin` error handling
httpie/cli/argparser.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-01-23: Fixed `--form` file upload mixed with redirected `stdin` error handling.
CHANGELOG.rst
httpie/__init__.py
httpie/cli/argparser.py
tests/test_httpie.py
tests/test_uploads.py

## Brad Solomon (brad.solomon.1124@gmail.com) on 2020-01-23: Clean up Python-version related PyPI classifiers (#841)
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2020-01-13: Update CHANGELOG.rst
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-01-12: Update brew formula
extras/httpie.rb

## Jakub Roztocil (jakub@roztocil.co) on 2020-01-12: Cleanup
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-01-12: Update Python version info
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-01-12: Ignore codecov upload failures
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2020-01-12: Fix version
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2020-01-12: v2.0.0
CHANGELOG.rst
Makefile
httpie/__init__.py
httpie/cli/requestitems.py
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-04: Cleanup
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-04: Fixes
CONTRIBUTING.rst
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-04: Fixes
CONTRIBUTING.rst
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-04: Set path in makefile
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-04: Fix tests
Makefile
tests/test_docs.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-04: Create Python virtual environment (via venv) for tests & development, etc.
.github/workflows/build.yml
.gitignore
CONTRIBUTING.rst
Makefile

## Martin Hellspong (martin.hellspong@factor10.com) on 2019-12-04: Fix make target in CONTRIBUTING.rst (#819)
CONTRIBUTING.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-04: Switch to explicitly listed directories to search in for `*.rst` #820
tests/test_docs.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-04: Merge remote-tracking branch 'origin/master'
## Roger Wernersson (roger.wernersson@factor10.com) on 2019-12-04: exclude site-packages from .rst file scanning (#820)
tests/test_docs.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-04: Merge remote-tracking branch 'origin/master'
## Roger Wernersson (roger.wernersson@factor10.com) on 2019-12-04: run rst2pseudoxml.py with shell=true (#821)
tests/test_docs.py

## Tim Gates (tim.gates@iress.com) on 2019-12-04: Fix simple typo: downland -> download (#823)
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-03: Cleanup
httpie/cli/constants.py
httpie/client.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-03: Tweak querystring parameters doc
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-02: Fix build
.github/workflows/build.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-02: Upgrade setuptools
.github/workflows/build.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-02: Add Python 3.8 build
.github/workflows/build.yml

## Semen Zhydenko (simeon.zhidenko@gmail.com) on 2019-12-02: withing -> within (#795)
tests/test_sessions.py

## onnadi-sa (51714064+onnadi-sa@users.noreply.github.com) on 2019-12-02: Fix typo (#808)
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-02: Skip test_config_file_inaccessible on Windows
tests/test_config.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-02: Ignore test cleanup rmtree errors (Win)
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-02: PEP8
tests/test_errors.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-02: Remove automatic config file creation to avoid concurrency issues.
CHANGELOG.rst
README.rst
httpie/cli/argparser.py
httpie/client.py
httpie/config.py
httpie/context.py
httpie/core.py
httpie/sessions.py
tests/test_config.py
tests/test_errors.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-02: cleanup
httpie/cli/requestitems.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-12-02: Cleanup
httpie/status.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-28: Update build.yml
.github/workflows/build.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-28: Update build.yml
.github/workflows/build.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-18: Add main entry point tests
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-18: Make `ExitStatus` subclass `IntEnum` to allow direct `int` comparisons
httpie/core.py
httpie/status.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-18: Make codecov fail loudly
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-18: Fix codecov token
.github/workflows/build.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-18: Fix step order
.github/workflows/build.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-18: codecov
.github/workflows/build.yml
Makefile
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-17: Typing & cleanup
httpie/cli/argtypes.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-17: Runnable KeyValueArgType.tokenize doctest
httpie/cli/argtypes.py
httpie/cli/requestitems.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-16: Cleanup
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-16: Add `httpie.status`
httpie/__init__.py
httpie/__main__.py
httpie/cli/definition.py
httpie/core.py
httpie/status.py
tests/test_cli.py
tests/test_errors.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_output.py
tests/test_redirects.py
tests/test_ssl.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: Simplify
.github/workflows/build.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: Build badge
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: Build on push via GitHub Actions
.github/workflows/build.yml
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: Build on push via GitHub Actions
.github/workflows/build.yml
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: Remove .travis.yml
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: worflow
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: worflow
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: worflow
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: worflow
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: worflow
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: worflow
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: workflow
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: workflow
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: coveralls token
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: workflow
.github/workflows/pythonpackage.yml
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: Update pythonpackage.yml
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: Update pythonpackage.yml
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: Update pythonpackage.yml
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: Update pythonpackage.yml
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-10: Update pythonpackage.yml
.github/workflows/pythonpackage.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-09: Update CHANGELOG.rst
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-04: Create CODE_OF_CONDUCT.md
CODE_OF_CONDUCT.md

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-04: Move compression out of adapter
httpie/client.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-03: Typos
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-03: CHANGELOG
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-03: Included tests in pypi package #182
MANIFEST.in

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-03: Add one-by-one processing of each HTTP request or response and --offline
CHANGELOG.rst
httpie/cli/argparser.py
httpie/cli/constants.py
httpie/cli/definition.py
httpie/client.py
httpie/core.py
httpie/downloads.py
httpie/output/streams.py
httpie/output/writer.py
httpie/sessions.py
tests/test_auth.py
tests/test_cli.py
tests/test_downloads.py
tests/test_errors.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_redirects.py
tests/test_sessions.py
tests/test_ssl.py
tests/test_uploads.py
tests/test_windows.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-02: Cleanup
httpie/client.py
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-01: Sessions
httpie/client.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-01: Refactor get_formatters_grouped
httpie/plugins/base.py
httpie/plugins/manager.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-01: Refactor client
httpie/cli/definition.py
httpie/client.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-09-01: Refactor `PluginManager`
httpie/plugins/manager.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: Annotate formatters and processing
httpie/output/formatters/colors.py
httpie/output/formatters/headers.py
httpie/output/formatters/json.py
httpie/output/processing.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: Fix unregister annotation
httpie/plugins/manager.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: CHANGELOG
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: Annotate plugins
httpie/output/processing.py
httpie/plugins/__init__.py
httpie/plugins/base.py
httpie/plugins/builtin.py
httpie/plugins/manager.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: Annotate and refactor streams.py
CHANGELOG.rst
httpie/cli/requestitems.py
httpie/output/streams.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: CHANGELOG
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: Improve --debug output formatting
httpie/client.py
httpie/context.py
httpie/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: Fix --ssl with --compress; refactor client
httpie/client.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: Refactoring
extras/brew-deps.py
httpie/cli/__init__.py
httpie/cli/argparser.py
httpie/cli/argtypes.py
httpie/cli/constants.py
httpie/cli/definition.py
httpie/cli/dicts.py
httpie/cli/exceptions.py
httpie/cli/requestitems.py
httpie/client.py
httpie/context.py
httpie/core.py
httpie/input.py
httpie/models.py
httpie/output/streams.py
httpie/sessions.py
httpie/utils.py
tests/test_auth.py
tests/test_auth_plugins.py
tests/test_cli.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_sessions.py
tests/test_ssl.py
tests/test_uploads.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: CHANGELOG
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: Document `$ALL_PROXY` support (close #676)
README.rst
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: Test that `--ignore-netrc` doesn't interfere with `--auth`
tests/test_auth.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-31: Allow bypassing .netrc with `--ignore-netrc` (close #730)
CHANGELOG.rst
README.rst
httpie/cli.py
httpie/input.py
httpie/utils.py
tests/test_auth.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-30: pep8
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-30: Python 3 annotations, super(), pathlib, etc.
httpie/__init__.py
httpie/__main__.py
httpie/cli.py
httpie/client.py
httpie/config.py
httpie/context.py
httpie/core.py
httpie/downloads.py
httpie/input.py
httpie/models.py
httpie/output/formatters/colors.py
httpie/output/processing.py
httpie/output/streams.py
httpie/plugins/base.py
httpie/plugins/manager.py
httpie/sessions.py
tests/test_cli.py
tests/test_config.py
tests/test_docs.py
tests/test_downloads.py
tests/test_httpie.py
tests/test_sessions.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-30: Update links to HTTPS
.editorconfig
CHANGELOG.rst
CONTRIBUTING.rst
README.rst
httpie/downloads.py
httpie/input.py
httpie/plugins/base.py
httpie/sessions.py
httpie/utils.py
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-30: Use set literal
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Don't fail if config dir not writeable (close #738)
CHANGELOG.rst
httpie/config.py
httpie/context.py
tests/test_config.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Merge branch 'mgsloan-allow-closed-stdin'
## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Allow stdin to be a closed fd #791
.travis.yml
CHANGELOG.rst
README.rst
httpie/context.py
httpie/input.py
tests/test_cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Merge branch 'allow-closed-stdin' of https://github.com/mgsloan/httpie into mgsloan-allow-closed-stdin
## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Reintroduce `$ https` command alias with `https://` as default scheme
.travis.yml
CHANGELOG.rst
README.rst
httpie/core.py
httpie/input.py
setup.py
tests/test_cli.py
tests/test_errors.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Use exact text from the three-clause BSD license (close #740)
LICENSE

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: CHANGELOG
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Refactor `--compress` tests
httpie/client.py
tests/test_compress.py
tests/test_httpie.py
tests/utils.py

## Aleksandr Vinokurov (aleksandr.vin@gmail.com) on 2019-08-29: Add compressed requests (#739)
AUTHORS.rst
httpie/cli.py
httpie/client.py
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: pep8
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Fix ``--timeout=0``
httpie/client.py
tests/test_errors.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Remove the default 30-second connection timeout limit
CHANGELOG.rst
README.rst
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Make `test_binary_suppresses_*` deterministic
tests/test_binary.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Disable default max headers limit and add --max-headers  (closes #802)
CHANGELOG.rst
README.rst
httpie/cli.py
httpie/client.py
tests/test_errors.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: pip3
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Changelog
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Python 2.7 support removal WIP
.travis.yml
README.rst
httpie/__init__.py
httpie/client.py
httpie/compat.py
httpie/core.py
httpie/downloads.py
httpie/input.py
httpie/models.py
httpie/output/streams.py
httpie/sessions.py
setup.py
tests/test_downloads.py
tests/test_output.py
tests/test_ssl.py
tests/utils.py
tox.ini

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: doc
tox.ini

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: fix tests
tox.ini

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: fix tests
.travis.yml
requirements-dev.txt
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: Temporarily disable macOS stock Python Travis build
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: fix test_ssl_version II
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-29: fix test_ssl_version on pypy
tests/test_ssl.py

## Rub├⌐n Dur├ín Balda (ruduran@users.noreply.github.com) on 2019-08-29: Fix tests (work in progress) (#796)
requirements-dev.txt
setup.py

## Jeff Byrnes (thejeffbyrnes@gmail.com) on 2019-08-29: Update homebrew formula for 1.0.3 (#801)
AUTHORS.rst
extras/httpie.rb

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-28: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-26: Update CHANGELOG.rst
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-26: Fix link
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-08-26: 1.0.3
CHANGELOG.rst
Makefile
httpie/__init__.py
requirements-dev.txt

## Jakub Roztocil (jakub@roztocil.co) on 2019-07-20: Update CHANGELOG.rst
CHANGELOG.rst

## Michael Sloan (mgsloan@gmail.com) on 2019-07-17: Allow stdin to be a closed fd
httpie/context.py
httpie/input.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-06-24: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-06-24: Fix comments
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-06-24: Changed the way the output filename is generated
CHANGELOG.rst
README.rst
httpie/downloads.py
tests/test_downloads.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-06-23: Create FUNDING.yml
.github/FUNDING.yml

## Harkirat Singh (harkirat1892@gmail.com) on 2019-04-10: Updated Readme to fix a typo (#767)
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2019-03-11: Add a bash here string example
README.rst

## Micka├½l Schoentgen (contact@tiger-222.fr) on 2019-02-04: Fix several ResourceWarning: unclosed file (#741)
httpie/input.py
tests/test_downloads.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-02-03: Add animation by @loranallensmith
README.rst
httpie.gif

## Jakub Roztocil (jakub@roztocil.co) on 2019-02-03: Brew cleanup
Makefile
extras/brew-deps.py

## Jakub Roztocil (jakub@roztocil.co) on 2019-02-03: Add `make brew-test`
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2019-02-03: Bump dependency versions #742
extras/get-homebrew-formula-vars.py
extras/httpie.rb
setup.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2019-01-09: Update LICENSE
LICENSE

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-14: 1.0.3-dev
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-14: v1.0.2
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-14: Changelog
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-14: Fix tests for installation with pyOpenSSL #729
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-14: Add `make pdf`
Makefile
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-14: Fix changelog
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2017-03-08: Don't call external URLs from tests #729
CHANGELOG.rst
httpie/__init__.py
tests/test_binary.py

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-06: Brew
extras/httpie.rb

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-03: Update screenshot
httpie.png

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-02: Homebrew formula for v1.0.0
extras/get-homebrew-formula-vars.py
extras/httpie.rb

## Jakub Rozto─ìil (jakub@roztocil.co) on 2018-11-02: Update CHANGELOG.rst
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-02: v1.0.0
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-02: Cleanup
httpie/cli.py
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-02: `exit 0` constant: `OK` => `SUCCESS` to avoid confusion w/ `HTTP 200 OK`
httpie/__init__.py
httpie/core.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_output.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-02: Changelog
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-02: Merge remote-tracking branch 'origin/master'
## Vladimir Berkutov (dair.targ@gmail.com) on 2018-11-02: #722: Add support for tls1.3 (#724)
README.rst
httpie/input.py

## Jakub Roztocil (jakub@roztocil.co) on 2018-11-02: Finish --style=auto for terminal ANSI colors and make it the default.
CHANGELOG.rst
httpie/cli.py
httpie/output/formatters/colors.py

## Ankit R. Gadiya (git@argp.in) on 2018-10-31: Fixed some lines (#723)
CONTRIBUTING.rst
README.rst

## Mat├║┼í Ferech (matus.ferech@gmail.com) on 2018-10-30: Add prog parameter to HTTPieArgumentParser (#715)
httpie/cli.py

## Matthew Leather (39400458+matthew16550@users.noreply.github.com) on 2018-09-08: Fix some broken documentation links (#703)
httpie/config.py
httpie/sessions.py

## Matthew Leather (39400458+matthew16550@users.noreply.github.com) on 2018-09-08: Fix for broken Travis builds on macOS with Python 3.7 (#704) (#705)
.travis.yml

## Matthew Leather (39400458+matthew16550@users.noreply.github.com) on 2018-09-08: Fix Tox using different Python than expected on macOS (#688) (#706)
.travis.yml
tox.ini

## 0xflotus (0xflotus@gmail.com) on 2018-09-03: fixed output for escaping rules (#700)
README.rst

## cclauss (cclauss@bluewin.ch) on 2018-07-25: Travis CI: Add Python 3.7 on linux to the testing (#690)
.travis.yml

## Jakub Rozto─ìil (jakub@roztocil.co) on 2018-07-22: Add v 0.9.9 CHANGELOG link
CHANGELOG.rst

## Jakub Rozto─ìil (jakub@roztocil.co) on 2018-07-22: Mention v0.9.9 in CHANGELOG
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2018-07-12: Travis
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2018-07-12: Travis
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2018-07-12: Travis CI Python versions; install fix
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2018-07-12: Fix travis.yml syntax
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2018-07-12: Build fixes and clean-up
.coveragerc
.gitignore
.travis.yml
CONTRIBUTING.rst
Makefile
extras/get-homebrew-formula-vars.py
httpie/core.py
httpie/downloads.py
httpie/input.py
httpie/output/formatters/json.py
httpie/sessions.py
pytest.ini
requirements-dev.txt
setup.cfg
tests/test_cli.py
tests/test_sessions.py
tests/utils.py
tox.ini

## Jakub Roztocil (jakub@roztocil.co) on 2018-07-12: Test --timeout with longer delay
tests/test_exit_status.py

## Jakub Roztocil (jakub@roztocil.co) on 2018-06-09: Fix pytest configuration
tests/conftest.py

## Jakub Roztocil (jakub@roztocil.co) on 2018-05-30: Doc improvements
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2018-05-30: Formatting
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2018-05-30: Section ordering
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2018-05-30: Add Cookies section to the docs
README.rst

## Piotr ┼Üliwka (contact@psliwka.info) on 2018-04-14: Support using styles from Pygments plugins (#663)
httpie/output/formatters/colors.py

## Theodore Dubois (tblodt@icloud.com) on 2018-04-11: Use parentheses in describing sessions (#664)
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2018-02-22: Make default HTTP headers case-insensitive
CHANGELOG.rst
httpie/client.py
tests/test_defaults.py

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-28: Remove a Python 2.6 mention from `extras_require`
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-28: Upgrade to latest requests
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-28: More robust urllib3 import
httpie/client.py

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-28: Rename `TestEnvironment` to `MockEnvironment` to avoid pytest warnings
tests/test_auth.py
tests/test_binary.py
tests/test_cli.py
tests/test_config.py
tests/test_defaults.py
tests/test_downloads.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_output.py
tests/test_sessions.py
tests/test_stream.py
tests/test_uploads.py
tests/test_windows.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-28: Start using dict comprehensions
httpie/__init__.py
httpie/client.py
httpie/input.py
httpie/plugins/manager.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-28: Removed Python 2.6 support
CHANGELOG.rst
README.rst
httpie/compat.py
httpie/input.py
httpie/utils.py
setup.py
tests/test_httpie.py
tox.ini

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-22: Fix rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-22: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-22: Delete appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-22: Remove AppVeyor II.
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-22: Remove AppVeyor
README.rst

## Ildar Sagdejev (specious@gmail.com) on 2017-12-22: Fix README (#641)
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-17: OS X => macOS
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-13: appveyor fix attempt II.
appveyor.yml

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-13: appveyor fix attempt
appveyor.yml

## Pablo Santiago Blum de Aguiar (scorphus@gmail.com) on 2017-05-17: Use function as source of styles for Fish completion
extras/httpie-completion.fish

## Pablo Santiago Blum de Aguiar (scorphus@gmail.com) on 2017-05-17: Remove duplicate option from Fish completion list
extras/httpie-completion.fish

## Jakub Roztocil (jakub@roztocil.co) on 2017-12-13: Merge pull request #633 from darshanime/version_number_fix
## Jakub Roztocil (jakub@roztocil.co) on 2017-12-13: Merge pull request #631 from CrazyPython/patch-2
## Jakub Roztocil (jakub@roztocil.co) on 2017-12-13: Merge pull request #630 from CrazyPython/patch-1
## Jakub Roztocil (jakub@roztocil.co) on 2017-12-13: Merge pull request #638 from gtback/update-contributing-rst
## Greg Back (gback@mitre.org) on 2017-12-07: Update CONTRIBUTING.rst to include correct Makefile targets.
CONTRIBUTING.rst

## darshanime (deathbullet@gmail.com) on 2017-11-18: fix env version attribute
httpie/config.py
tests/test_config.py

## James (Jamtlu@gmail.com) on 2017-11-14: Remove 2.6
.travis.yml

## James (Jamtlu@gmail.com) on 2017-11-13: Clarify error message
httpie/input.py

## Jakub Roztocil (jakub@roztocil.co) on 2017-10-04: Merge pull request #614 from watersalesman/master
## Randy Ramos (rramos1295@gmail.com) on 2017-10-02: List DNF as Fedora package manager in README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2017-09-07: Update AppVeyor
README.rst
appveyor.yml

## Jakub Roztocil (jakub@roztocil.co) on 2017-09-06: Update copyright year
LICENSE

## Jakub Roztocil (jakub@roztocil.co) on 2017-09-06: Fix Gitter link
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2017-07-20: Merge pull request #584 from scorphus/hotfix/new-requests
## Jakub Roztocil (jakub@roztocil.co) on 2017-07-20: Merge pull request #589 from alappe/patch-1
## Jakub Roztocil (jakub@roztocil.co) on 2017-07-20: Merge pull request #591 from DavidOliver/patch-1
## David Oliver (DavidOliver@users.noreply.github.com) on 2017-06-30: Fix sentence on overriding default timeout in readme
README.rst

## Andreas Lappe (nd@off-pist.de) on 2017-06-26: Update README.rst
README.rst

## Pablo Santiago Blum de Aguiar (scorphus@gmail.com) on 2017-05-17: Support requests>=2.14.0
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2017-03-12: Merge pull request #568 from dsego/dsego/ansi-colors
## Jakub Roztocil (jakub@roztocil.co) on 2017-03-12: Fix link
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2017-03-12: Travis `cache: pip`
.travis.yml

## Davorin S╠îego (davorin.sego@gmail.com) on 2017-03-11: Oops, remove semicolons
httpie/output/formatters/colors.py

## Davorin S╠îego (davorin.sego@gmail.com) on 2017-03-11: New style option that applies the terminal ANSI color scheme
httpie/cli.py
httpie/output/formatters/colors.py

## Davorin S╠îego (davorin.sego@gmail.com) on 2017-03-11: Revert "Follow terminal ANSI color styles"
httpie/cli.py
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.co) on 2017-03-10: Update links
.travis.yml
AUTHORS.rst
CHANGELOG.rst
CONTRIBUTING.rst
README.rst
extras/httpie.rb
httpie/cli.py
httpie/client.py
httpie/downloads.py
httpie/input.py
httpie/plugins/base.py
httpie/plugins/builtin.py
setup.py
tests/README.rst
tests/test_auth.py
tests/test_defaults.py
tests/test_httpie.py
tests/test_output.py
tests/test_regressions.py
tests/test_sessions.py

## Davorin S╠îego (davorin.sego@gmail.com) on 2017-03-06: Follow terminal ANSI color styles
httpie/cli.py
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.co) on 2017-03-01: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2017-02-17: Add --verify true/false tests and CHANGELOG
CHANGELOG.rst
httpie/__init__.py
httpie/cli.py
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2017-02-17: Merge pull request #560 from hangtwenty/dummyproof-cli-param-verify
## Michael Floering (mfloering@veracode.com) on 2017-02-09: Turn --verify=False/True to --verify=no/yes
httpie/client.py

## Jakub Roztocil (jakub@roztocil.co) on 2017-02-09: Merge pull request #558 from RobDesideri/patch-1
## Roberto Desideri (robertodesideri@outlook.com) on 2017-02-09: Update pip official website url
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2017-02-07: Merge pull request #494 from keik/patch-1
## Jakub Roztocil (jakub@roztocil.co) on 2017-02-07: Merge pull request #555 from rootulp/patch-1
## Jakub Roztocil (jakub@roztocil.co) on 2017-02-07: Merge pull request #557 from robertbenjamin/fix-doc-typo
## Robert Benjamin (rotberj@gmail.com) on 2017-02-02: Fix typo in the docs
README.rst

## Rootul Patel (rootulp@gmail.com) on 2017-01-22: Gitter Badge: flat-square style
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2017-01-08: Merge pull request #552 from duboviy/master
## Eugene Duboviy (eugene.dubovoy@gmail.com) on 2017-01-08: Update setup.py
setup.py

## Eugene Duboviy (eugene.dubovoy@gmail.com) on 2017-01-08: Update appveyor.yml
appveyor.yml

## Eugene Duboviy (eugene.dubovoy@gmail.com) on 2017-01-08: Update .travis.yml
.travis.yml

## Eugene Duboviy (eugene.dubovoy@gmail.com) on 2017-01-08: Update tox.ini
tox.ini

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-17: Alternatives
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-17: Added link to `httpcat`
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-10: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-09: Fix PyPi README rendering
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-08: AWS / Amazon S3 auth plugin link
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-08: Doc
extras/httpie.rb

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-08: Update README with new plugin repos location
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-08: Redme
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-08: Update Homebrew formula
extras/httpie.rb

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-08: 0.9.8
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-08: Fix --auth-type help
README.rst
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-08: Keep the latest submitted Homebrew formula in extras/ for testing
extras/httpie.rb

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-08: 0.9.7
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-08: Added `ExitStatus.PLUGIN_ERROR` (7)
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-07: Fix PyPi link
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-07: Docs
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-07: Docs
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-07: Docs
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-12-07: Docs
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-11-24: Cleanup
httpie/cli.py
tests/test_auth_plugins.py
tests/test_binary.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-11-23: pep8
httpie/input.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-11-23: Fix Python 2.6
tests/test_auth_plugins.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-11-23: Cleanup
tests/test_auth_plugins.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-11-23: Add more plugin API tests
httpie/cli.py
httpie/input.py
tests/test_auth.py
tests/test_auth_plugins.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-11-23: Cleanup
httpie/cli.py
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-11-23: Cleanup/docstring
httpie/plugins/base.py
tests/test_auth_plugins.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-11-23: Extend auth plugin API
CHANGELOG.rst
httpie/cli.py
httpie/client.py
httpie/input.py
httpie/plugins/base.py
httpie/plugins/builtin.py
httpie/plugins/manager.py
httpie/sessions.py
tests/test_auth.py
tests/test_auth_plugins.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-11-23: Test case for `Host` header removal (unimplemented feature)
tests/test_httpie.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-10-28: Merge pull request #533 from kigawas/patch-1
## Ryan Lee (to.be.impressive@gmail.com) on 2016-10-28: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-10-26: Changelog
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-10-26: Clean-up
tests/test_exit_status.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-10-26: Changelog
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-10-26: Exit with status 130 on CTRL-C
CHANGELOG.rst
httpie/__init__.py
httpie/__main__.py
httpie/core.py
tests/test_exit_status.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-10-26: Fixed test
tests/test_regressions.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-10-26: Need a `main()`
httpie/__main__.py
tests/test_regressions.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-10-26: Stricter KeyboardInterrupt silencing
httpie/__main__.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-09-17: Add Twitter link
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-09-12: Update config and session file help URLs
httpie/config.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-09-12: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-09-12: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-09-12: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-09-11: Updated config docs
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-09-11: Updated config docs
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-09-11: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-09-11: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-09-06: CHANGELOG
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-09-06: Handle curses-free Pythons
httpie/__init__.py
httpie/context.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-09-06: Merge pull request #516 from dongweiming/fix-496
## dongweiming (ciici123@hotmail.com) on 2016-09-01: Fix Issue #496
httpie/cli.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-08-14: Update CHANGELOG.rst
CHANGELOG.rst

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-08-14: Merge pull request #503 from zquestz/patch-1
## Josh Ellithorpe (quest@mac.com) on 2016-08-13: Updated README.rst to add Arch Linux install docs.
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-08-13: v0.9.6
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-08-13: Fixed Makefile
Makefile
extras/get-homebrew-formula-vars.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-08-13: Upgrade Pygments version
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-08-13: v0.9.5
CHANGELOG.rst
Makefile
httpie/__init__.py
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-08-13: Strip request header values
extras/get-homebrew-formula-vars.py
httpie/client.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-08-11: Merge pull request #501 from ii-v/master
## ii-v (iiv@openmailbox.org) on 2016-08-11: Merge pull request #1 from ii-v/ii-v-patch-1
## ii-v (iiv@openmailbox.org) on 2016-08-11: Fixed spelling mistage `GitHib` to `GitHub`
AUTHORS.rst

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-07-29: Merge pull request #493 from medecau/codestyle_environment
## KATO Kei (k4t0.kei@gmail.com) on 2016-07-27: Fix typo
httpie/core.py

## Pedro Rodrigues (medecau@gmail.com) on 2016-07-26: useful info
.travis.yml
tox.ini

## Pedro Rodrigues (medecau@gmail.com) on 2016-07-26: force os to be linux (+1 squashed commit) Squashed commits: [444c56d] no vars for you (+1 squashed commit) Squashed commits: [c7d1bf9] added pycodestyle environment to travis config
.travis.yml

## Pedro Rodrigues (medecau@gmail.com) on 2016-07-19: codestyle fixes
httpie/cli.py
httpie/core.py
tests/test_cli.py

## Pedro Rodrigues (medecau@gmail.com) on 2016-07-19: separate environment to test codestyle as proposed by @sigmavirus24
tox.ini

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-08: Fix formatting
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-08: Added related projects
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-04: PEP8. clean-up
httpie/client.py
httpie/compat.py
httpie/downloads.py
httpie/input.py
httpie/plugins/builtin.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Clean-up
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Fixed README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Fixed README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Added -I  as a shortcut for --ignore-stdin
CHANGELOG.rst
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Upgrade requests to 2.10.0 to enable optional  SOCKS support
CHANGELOG.rst
README.rst
setup.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Fish shell completion
CHANGELOG.rst
extras/httpie-completion.bash
extras/httpie-completion.fish

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-07-02: Merge pull request #459 from dickeyxxx/fish-completion
## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: More liberal default JSON Accept header
CHANGELOG.rst
README.rst
httpie/client.py
tests/test_defaults.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Clean-up
README.rst
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Added --default-scheme <URL_SCHEME>
CHANGELOG.rst
README.rst
httpie/cli.py
httpie/input.py
tests/test_cli.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-07-02: Merge pull request #401 from lgarron/default-scheme
## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Skip pypy3 tests on TravisCI
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Fix tests
tests/test_cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Added the ability to unset headers
CHANGELOG.rst
README.rst
httpie/input.py
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Fix CHANGELOG
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Typos
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-02: Document preference for Python 3
CHANGELOG.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-01: 1.0.0-dev
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-01: v0.9.4
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-01: Cleanup
httpie/output/formatters/json.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-01: Be more liberal when detecting JSON in the formatter
httpie/output/formatters/json.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-07-01: Rename --print-others to --history-print.
CHANGELOG.rst
README.rst
httpie/cli.py
httpie/core.py
httpie/input.py
tests/test_redirects.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-04-28: Merge pull request #468 from Natim/master
## R├⌐my HUBSCHER (rhubscher@mozilla.com) on 2016-04-28: Update readthedocs links.
httpie/client.py
setup.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-04-20: Merge pull request #463 from KyleAMathews/patch-1
## Kyle Mathews (mathews.kyle@gmail.com) on 2016-04-18: Remove extra backtick.
README.rst

## Jeff Dickey (dickeyxxx@gmail.com) on 2016-04-06: added completions for fish shell
httpie-completion.fish

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-18: Updated README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-18: Removed XML formatter
CHANGELOG.rst
httpie/output/formatters/xml.py
httpie/plugins/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-17: Handle that os.pathconf is posix-only
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-17: Fixed #451 - OSError: [Errno 36] File name too long
CHANGELOG.rst
httpie/downloads.py
tests/test_downloads.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-17: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-10: README
CHANGELOG.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-09: Added test for -F shortcut
tests/test_redirects.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-09: Added test_verbose_implies_all
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-09: Changed the version icon label to include to word "stable"
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-07: Add `Accept-Encoding: identity` for --download
httpie/downloads.py
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-07: Typo
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-06: Replace --show-redirects with --all and add --print-others, -P
CHANGELOG.rst
README.rst
httpie/cli.py
httpie/core.py
httpie/input.py
httpie/output/streams.py
tests/test_redirects.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-06: Run tests against both HTTP and HTTPS
tests/conftest.py
tests/test_auth.py
tests/test_binary.py
tests/test_downloads.py
tests/test_httpie.py
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-06: Make fruity default style one Windows
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-05: Add link to contributors
AUTHORS.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-05: Improved --debug output
CHANGELOG.rst
httpie/client.py
httpie/context.py
httpie/core.py
httpie/utils.py
tests/test_errors.py
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-03: Cleanup tests
tests/test_auth.py
tests/test_cli.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_output.py
tests/test_stream.py
tests/test_unicode.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-03: Fix CHANGELOG
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-03: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-03: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-03: Fixed test_rst_file_syntax error message
tests/test_docs.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-03: Fixed README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-03: Removed the "implicit_content_type" config option
CHANGELOG.rst
README.rst
httpie/config.py
httpie/input.py
tests/test_config.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-03: Nobody ain't got time for that
tests/test_exit_status.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Cleanup
.coveragerc
CHANGELOG.rst
README.rst
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Fixed coverage
.coveragerc

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Cleanup
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Improved failed test output
CHANGELOG.rst
httpie/__init__.py
pytest.ini
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Fix coveralls integration
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Fix coveralls integration
httpie/client.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Changel
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Added --ssl=<PROTOCOL_VERSION>
CHANGELOG.rst
README.rst
httpie/cli.py
httpie/client.py
httpie/input.py
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Run positive tests first
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: CI
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: CI
appveyor.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: CI
.travis.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Appveyor: added Python 3.5 build
appveyor.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Appveyor
appveyor.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Cleanup
httpie/cli.py
httpie/client.py
httpie/models.py
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Cleanup
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-02: Added a short timeout for test requests
README.rst
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Mention URL escaping
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Test suite cleanup
tests/test_defaults.py
tests/test_sessions.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Cleanup
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Test suite improvements
tests/utils.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Copy
httpie/cli.py
httpie/core.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Fixed args for Python 2.x
httpie/core.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Refactored main() into program()  + main()
httpie/core.py
tests/test_errors.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Ignore redirected stdout with --output, -o
CHANGELOG.rst
Makefile
httpie/cli.py
httpie/core.py
httpie/input.py
tests/test_output.py
tests/test_windows.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Fixed get_lexer()
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Fixed json absolute import
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: JSON detection improvements
README.rst
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Added JSON detection when ``--json, -j`` is set
.gitignore
CHANGELOG.rst
README.rst
httpie/output/formatters/colors.py
httpie/output/formatters/json.py
httpie/output/streams.py
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Fixed README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Added support section
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Added gitter chat
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-03-01: Added gitter chat
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Capitalization II
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Capitalization
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Updated travis badge title
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Travis
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Travis
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Travis
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Travis
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Travis
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Travis
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Travis
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Fix travis
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Fix travis
.travis.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: OSX build
.travis.yml

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-02-29: Fix appveyor
appveyor.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Refactoring
httpie/core.py
httpie/downloads.py
httpie/output/streams.py
tests/test_downloads.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Cleanup
CHANGELOG.rst
tests/test_redirects.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Fixed --max-redirects
README.rst
httpie/client.py
httpie/core.py
tests/test_redirects.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Added --show-redirects and --max-redirects
CHANGELOG.rst
README.rst
httpie/__init__.py
httpie/cli.py
httpie/core.py
tests/fixtures/__init__.py
tests/test_redirects.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-29: Show redirects WIP
httpie/core.py
httpie/sessions.py

## James Carr (jc3212@ic.ac.uk) on 2014-07-31: Implemented --max-redirects option
httpie/cli.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-02-29: Update CHANGELOG.rst
CHANGELOG.rst

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-02-29: Update CHANGELOG.rst
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-28: Updated CHANGELOG
CHANGELOG.rst
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-28: Document -A as a short name for --auth-type
CHANGELOG.rst
README.rst

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-02-28: Merge pull request #432 from hangtwenty/master
## Jakub Roztocil (jakub@roztocil.co) on 2016-02-28: More robust mime type parsing
httpie/output/formatters/colors.py
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-28: Fix README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-28: Explain how to send fieldnames and headers starting with '-'
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-28: Cleanup
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-28: Fixed --download with --session
httpie/sessions.py
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-28: Parser => HTTPieArgumentParser
httpie/cli.py
httpie/input.py
tests/test_cli.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-28: Mention MacPorts installation method
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-28: Updated tarball URL
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-28: Updated download example URLs
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-28: Detect Content Type of file uploaded in multipart/form-data request
.gitignore
CHANGELOG.rst
httpie/input.py
tests/test_uploads.py

## Marcin Szewczyk (marcin.szewczyk@wodny.org) on 2015-10-24: When possible, guess the content-type of the file being sent
httpie/input.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-02-17: Typo
CHANGELOG.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-02-17: Changed the default color style back to solarized
CHANGELOG.rst
httpie/output/formatters/colors.py

## Michael Floering (mfloering@veracode.com) on 2016-01-22: Small fix for Python 2.6 compatibility.
tests/test_auth.py

## Michael Floering (mfloering@veracode.com) on 2016-01-22: Merge remote-tracking branch 'upstream/master'
## Michael Floering (mfloering@veracode.com) on 2016-01-22: add `-A` as short arg for `--auth-type`
httpie/cli.py
tests/test_auth.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-01-18: Merge pull request #429 from pra85/patch-1
## Prayag Verma (prayag.verma@gmail.com) on 2016-01-18: Update license year range to 2016
LICENSE

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-01-15: Added guardian/httpie-hmac-auth
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2016-01-02: Makefile improvements
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2016-01-02: Makefile improvements
CONTRIBUTING.rst
Makefile

## Jakub Roztocil (jakub@roztocil.co) on 2016-01-02: Fixed tox.ini and improved tests and  CONTRIBUTING.txt
CONTRIBUTING.rst
Makefile
httpie/config.py
tests/utils.py
tox.ini

## Jakub Roztocil (jakub@roztocil.co) on 2016-01-01: 1.0.0-dev
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-01-01: v0.9.3
CHANGELOG.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-01-01: Fix pytest configuration
pytest.ini

## Jakub Roztocil (jakub@roztocil.co) on 2016-01-01: Update pytest configuration
pytest.ini
tox.ini

## Jakub Roztocil (jakub@roztocil.co) on 2016-01-01: Update setuptools on Appveyor
appveyor.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-01-01: Update pip on Appveyor
appveyor.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-01-01: Update get-pip.py URL
appveyor.yml

## Jakub Roztocil (jakub@roztocil.co) on 2016-01-01: PEP8
httpie/client.py

## Jakub Roztocil (jakub@roztocil.co) on 2016-01-01: Undo 'Fix "mock requires setuptools>=17.1. Aborting installation" on Win+Py3'
setup.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-01-01: Merge pull request #396 from pathcl/master
## Jakub Roztocil (jakub@roztocil.co) on 2016-01-01: Fix "mock requires setuptools>=17.1. Aborting installation" on Win+Py3
setup.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-01-01: Merge pull request #382 from konopski/master
## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-01-01: Merge pull request #386 from honorabrutroll/dev
## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-01-01: Merge pull request #419 from hangtwenty/master
## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-01-01: Merge pull request #417 from yansal/patch-1
## Jakub Rozto─ìil (jakub@roztocil.co) on 2016-01-01: Merge pull request #421 from Altreus/patch-1
## Jakub Rozto─ìil (jakub@roztocil.co) on 2015-12-28: Merge pull request #424 from t-mart/master
## Tim Martin (tim@timmart.in) on 2015-12-28: Remove duplicate setup.py test option
setup.py

## Alastair McGowan-Douglas (altreus@altre.us) on 2015-12-15: Aitch already has an official spelling - use it
README.rst

## Michael Floering (mfloering@veracode.com) on 2015-12-02: Fail gracefully if disable_warnings not available
httpie/client.py

## Yann (yannsalaun1@gmail.com) on 2015-11-27: Fix typo in CONTRIBUTING.rst
CONTRIBUTING.rst

## Lucas Garron (lgarron@chromium.org) on 2015-10-28: Add a --default-scheme argument.
httpie/cli.py
httpie/input.py

## Luis San Martin (lsanmartinr@gmail.com) on 2015-10-22: PEP8 errors
httpie/cli.py
httpie/input.py
httpie/utils.py
setup.py
tests/fixtures.py
tests/test_auth.py
tests/test_docs.py
tests/test_sessions.py
tests/test_uploads.py

## Lukasz Konopski (konopski@users.noreply.github.com) on 2015-10-21: str conversion
httpie/input.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2015-10-07: Merge pull request #387 from yurimalheiros/patch-1
## Yuri Malheiros (yurimalheiros@gmail.com) on 2015-10-07: Update README.rst
README.rst

## honorabrutroll (edward.yang6771@gmail.com) on 2015-10-04: Fixed AUTHORS.rst
AUTHORS.rst

## honorabrutroll (edward.yang6771@gmail.com) on 2015-10-04: Add Edward Yang to AUTHORS.rst
AUTHORS.rst

## honorabrutroll (edward.yang6771@gmail.com) on 2015-10-04: Change pretty option processor to only raise error when using output file
httpie/input.py

## Lukasz Konopski (ext.lukasz.konopski@dsv.com) on 2015-09-21: [#381] --auth fails on windows
httpie/input.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2015-09-11: Disable OSX travis builds for now
.travis.yml

## Jakub Rozto─ìil (jakub@roztocil.co) on 2015-09-01: Update README.rst
README.rst

## Jakub Rozto─ìil (jakub@roztocil.co) on 2015-09-01: Merge pull request #375 from hoatle/jwt-auth-plugin-reference
## Jakub Rozto─ìil (jakub@roztocil.co) on 2015-08-31: Merge pull request #377 from mblayman/fix-trasnsport
## Matt Layman (matthewlayman@gmail.com) on 2015-08-30: Add Matt Layman to AUTHORS.
AUTHORS.rst

## Matt Layman (matthewlayman@gmail.com) on 2015-08-30: Fix typo in method name of plugin manager.
httpie/client.py
httpie/plugins/manager.py

## hoatle (hoatle@teracy.com) on 2015-08-24: mention httpie-jwt-auth plugin on README
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2015-07-03: Updated links II.
.travis.yml
AUTHORS.rst
CHANGELOG.rst
CONTRIBUTING.rst
appveyor.yml
httpie/cli.py
httpie/client.py
httpie/config.py
httpie/downloads.py
httpie/input.py
httpie/plugins/base.py
httpie/plugins/builtin.py
httpie/sessions.py
setup.py
tests/README.rst
tests/test_auth.py
tests/test_defaults.py
tests/test_httpie.py
tests/test_output.py
tests/test_regressions.py
tests/test_sessions.py

## Jakub Rozto─ìil (jakub@roztocil.co) on 2015-07-03: Updated links.
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2015-06-30: Fixed link to httpie-edgegrid
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2015-06-30: Added a link to the httpie-edgegrid plugin.
README.rst

## Jakub Roztocil (jakub@roztocil.co) on 2015-06-26: Converted tabs to spaces.
httpie-completion.bash

## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-04-24: Merge pull request #337 from joaodelgado/json-serialization
## Joao Delgado (joaomtdelgado@gmail.com) on 2015-04-11: Only serialize json if data is a dict instance
httpie/client.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-03-25: Added mock to tests_require
setup.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-03-25: Update CHANGELOG.rst
CHANGELOG.rst

## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-03-25: Update CHANGELOG.rst
CHANGELOG.rst

## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-03-25: Merge pull request #300 from msabramo/print_info_about_request_on_error
## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-03-25: Merge pull request #319 from fay-jai/license
## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-03-25: Merge pull request #330 from mihirvj/bash-completion
## Mihir Joshi (mihir.coldplay@gmail.com) on 2015-03-24: See #326
httpie-completion.bash

## Jakub Roztocil (jakub@roztocil.name) on 2015-03-13: Added .editorconfig.
.editorconfig

## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-03-10: Merge pull request #321 from ifdattic/patch-1
## Andrew Marcinkevi─ìius (andrew.web@ifdattic.com) on 2015-03-10: Fix typos, improve readability
README.rst

## Willson Mock (willson.mock@gmail.com) on 2015-03-08: Update license with up-to-date year
LICENSE

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-28: Fixed --debug output
httpie/client.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-24: Typo
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-24: README
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-24: Clean up `compat` and fix `is_pypy`.
httpie/compat.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-24: 1.0.0-dev
CHANGELOG.rst
httpie/__init__.py
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-24: 0.9.2
CHANGELOG.rst
httpie/__init__.py
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-24: Use absolute links to LICENCE, etc.
CHANGELOG.rst
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-24: Don't depend on `requests.compat`
httpie/compat.py
httpie/context.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-02-16: Update requirements-dev.txt
requirements-dev.txt

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-16: Include AUTHORS.rst in dist; metadata cleanup
LICENSE
MANIFEST.in
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-16: README fixes
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-16: Extracted changes from README into a proper CHANGELOG file
CHANGELOG.rst
MANIFEST.in
README.rst

## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-02-16: Merge pull request #312 from msabramo/patch-5
## Jakub Roztocil (jakub@roztocil.name) on 2015-02-16: Disable urllib3's "Unverified HTTPS request is being made" warnings
httpie/client.py

## Marc Abramowitz (marc@marc-abramowitz.com) on 2015-02-08: Increase test coverage for error handling
httpie/core.py
requirements-dev.txt
tests/test_errors.py

## Marc Abramowitz (marc@marc-abramowitz.com) on 2015-02-04: Print info about request on error
httpie/core.py

## Marc Abramowitz (marc@marc-abramowitz.com) on 2015-02-15: test_ssl.py: Remove skip failures on PyPy
tests/test_ssl.py

## Marc Abramowitz (marc@marc-abramowitz.com) on 2015-02-15: tox.ini: Use pytest-httpbin>=0.0.6
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-15: Fixed TOC
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-15: README
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-15: README
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-15: Tweak badge style
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-15: Use shields.io badges
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-15: README
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-15: README
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-15: Added a PyPy incompatibility workaround.
httpie/compat.py
httpie/input.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-14: Temporarily skip SSL tests on PyPy due to #308
httpie/compat.py
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-14: Default --style to "monokai"
README.rst
httpie.png
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-14: Updated screenshot
httpie.png

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-14: The default color --style is now "fruity"
README.rst
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-14: Update README examples with the new default `Accept-Encoding` value used by Requests.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-14: Changed the default JSON `Content-Type` to `application/json`.
README.rst
httpie/client.py
tests/test_defaults.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-02-10: Merge pull request #306 from msabramo/patch-4
## Marc Abramowitz (marc@marc-abramowitz.com) on 2015-02-09: .travis.yml: sudo false for Docker containers
.travis.yml

## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-02-10: Merge pull request #303 from msabramo/coveralls_only_one
## Marc Abramowitz (marc@marc-abramowitz.com) on 2015-02-09: .travis.yml: Only do coveralls on newest python
.travis.yml

## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-02-10: Merge pull request #304 from msabramo/patch-2
## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-02-10: Merge pull request #305 from msabramo/patch-3
## Marc Abramowitz (marc@marc-abramowitz.com) on 2015-02-09: compat.py: Add pragma no covers
httpie/compat.py

## Marc Abramowitz (marc@marc-abramowitz.com) on 2015-02-09: Mark test_session_unicode as xfail
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-07: README
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-07: 1.0.0-dev
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-07: v0.9.1
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-07: HTTP/2 has no minor versions.
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-07: Prevent a circular import issue.
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-06: Handle HTTP/2 responses
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-06: Added a link to @pd's httpie-api-auth plugin
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-05: Cleanup
httpie/client.py
httpie/plugins/manager.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-05: Added support for transport adapter plugins
httpie/client.py
httpie/plugins/__init__.py
httpie/plugins/base.py
httpie/plugins/manager.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-02-05: Allow custom URL schemes
httpie/input.py
tests/test_cli.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-01-31: Added a coveralls badge.
README.rst

## Jakub Rozto─ìil (jakub@roztocil.name) on 2015-01-31: Merge pull request #297 from msabramo/patch-1
## Marc Abramowitz (marc@marc-abramowitz.com) on 2015-01-31: README.rst: suppor => support
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-01-31: Fixed version link
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-01-31: 1.0.0-dev
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-01-31: v0.0.9
README.rst
requirements-dev.txt

## Jakub Roztocil (jakub@roztocil.name) on 2015-01-24: README
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-01-24: Extended SSL documentation.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2015-01-23: Added test client SSL certs
httpie/__init__.py
tests/client_certs/client.crt
tests/client_certs/client.key
tests/client_certs/client.pem

## Jakub Roztocil (jakub@roztocil.name) on 2015-01-23: Added tests for client as well as server SSL certificate handling.
tests/test_ssl.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-01-23: --certkey is now --cert-key
README.rst
httpie/cli.py
httpie/client.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-01-23: Pypy3 (2.4.0) curses bug workaround.
httpie/context.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-01-23: Work around missing `object_pairs_hook` in Python 2.6
httpie/compat.py
httpie/input.py
httpie/utils.py
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.name) on 2015-01-23: Merge branch 'fix-268' of https://github.com/asnelzin/httpie into asnelzin-fix-268
## Jakub Roztocil (jakub@roztocil.name) on 2015-01-19: Exit with 0 for --version and --help (closes #293).
httpie/core.py
tests/test_httpie.py

## Alexander Nelzin (asnelzin@gmail.com) on 2014-11-13: Fixed and added test for JSON properties order.
httpie/input.py
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-10-20: Fixed multiple uploads with the same  field name
README.rst
httpie/config.py
httpie/context.py
httpie/input.py
tests/test_cli.py
tests/test_uploads.py
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2014-09-16: Cleanup.
httpie/input.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-09-10: Cleanup
httpie/input.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-09-25: Merge pull request #260 from brakhane/master
## Dennis Brakhane (dennis.brakhane@inoio.de) on 2014-09-24: Fallback to JSON highlighting if subtype contains json
AUTHORS.rst
httpie/output/formatters/colors.py
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-09-08: Changelog
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-09-08: Merge remote-tracking branch 'origin/master'
## Jakub Roztocil (jakub@roztocil.name) on 2014-09-08: Improved terminal color depth detection via curses
httpie/context.py
httpie/output/formatters/colors.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-09-08: Removed pytest-xdist
Makefile
requirements-dev.txt
tox.ini

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-09-07: Merge pull request #249 from frewsxcv/patch-1
## Jakub Roztocil (jakub@roztocil.name) on 2014-09-07: Fixed --output=/dev/null on Linux
README.rst
httpie/input.py
tests/test_regressions.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-09-05: Changelog typo.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-09-05: '\' only escapes separator characters in req-items
README.rst
httpie/input.py
tests/test_cli.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-09-05: Added RequestItems named tuple for convenience.
httpie/input.py
setup.py
tests/test_cli.py

## Corey Farwell (coreyf@rwell.org) on 2014-08-15: Enable testing on PyPy 3
.travis.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-07-18: Handle empty passwords in URL credentials
README.rst
httpie/input.py
tests/test_auth.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-06-28: Cleanup
README.rst
httpie/downloads.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-07-17: Merge pull request #241 from ametaireau/patch-1
## Alexis Metaireau (alexis@notmyidea.org) on 2014-07-17: Add the hawk plugin
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-06-28: Fixed `python setup.py test`
setup.py
tests/test_regressions.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-06-28: Run tests against local httpbin instance via pytest-httpbin.
httpie/models.py
requirements-dev.txt
setup.py
tests/test_auth.py
tests/test_binary.py
tests/test_cli.py
tests/test_defaults.py
tests/test_downloads.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_output.py
tests/test_regressions.py
tests/test_sessions.py
tests/test_stream.py
tests/test_unicode.py
tests/test_uploads.py
tests/test_windows.py
tests/utils.py
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2014-06-28: Mention "brew install httpie --HEAD".
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-06-28: Fixed custom Host
httpie/models.py
tests/test_regressions.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-06-28: PEP8
setup.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-06-24: Fixed README formatting
README.rst

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-06-24: Added `$ brew install httpie` to README
README.rst

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-06-15: Merge pull request #225 from rockymeza/docs_grep_fix
## Rocky Meza (rocky@fusionbox.com) on 2014-06-15: Fixed the order of args to grep in README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-06-03: Fixed tests.
httpie/core.py
tests/test_sessions.py
tests/test_unicode.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-05-26: Merge pull request #222 from felixbuenemann/patch-1
## Felix Bu╠ênemann (buenemann@louis.info) on 2014-05-26: Add info about SNI on Python 2.x to README
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-05-17: Fixed --timeout
setup.py
tests/test_exit_status.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-05-14: Merge pull request #220 from frewsxcv/patch-1
## Jakub Roztocil (jakub@roztocil.name) on 2014-05-14: Added OSX to Travis CI config.
.travis.yml

## Corey Farwell (coreyf@rwell.org) on 2014-05-12: Add supported, relevant Python version classifers
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-05-12: Merge branch 'master' of github.com:jkbr/httpie
## Corey Farwell (coreyf@rwell.org) on 2014-05-11: Enable testing on Python 3.4
.travis.yml

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-05-09: Update CONTRIBUTING.rst
CONTRIBUTING.rst

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-05-09: Update CONTRIBUTING.rst
CONTRIBUTING.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-28: Converted built-in formatters to formatter plugins.
httpie/__init__.py
httpie/cli.py
httpie/client.py
httpie/compat.py
httpie/config.py
httpie/core.py
httpie/input.py
httpie/models.py
httpie/output/formatters/__init__.py
httpie/output/formatters/colors.py
httpie/output/formatters/headers.py
httpie/output/formatters/json.py
httpie/output/formatters/xml.py
httpie/output/processing.py
httpie/output/processors/__init__.py
httpie/output/processors/base.py
httpie/output/streams.py
httpie/plugins/__init__.py
httpie/plugins/base.py
httpie/plugins/builtin.py
httpie/plugins/manager.py
httpie/sessions.py
tests/test_output.py
tests/test_unicode.py
tests/utils.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-05-12: Merge pull request #219 from frewsxcv/patch-1
## Corey Farwell (coreyf@rwell.org) on 2014-05-11: Enable testing on Python 3.4
.travis.yml

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-05-09: Update CONTRIBUTING.rst
CONTRIBUTING.rst

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-05-09: Update CONTRIBUTING.rst
CONTRIBUTING.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-05-08: Make sure session and default headers play nice
README.rst
httpie/client.py
httpie/sessions.py
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-05-05: Fixed .rst syntax.
AUTHORS.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-05-05: New URL.
.travis.yml
AUTHORS.rst
CONTRIBUTING.rst
README.rst
appveyor.yml
httpie/cli.py
httpie/client.py
httpie/config.py
httpie/downloads.py
httpie/input.py
httpie/plugins/base.py
httpie/plugins/builtin.py
httpie/sessions.py
setup.py
tests/README.rst
tests/test_defaults.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-28: Fixed Makefile, added setup.cfg.
Makefile
setup.cfg

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-28: Added wheel support
.travis.yml
CONTRIBUTING.rst
MakeFile
requirements-dev.txt
setup.py
tests/test_output.py
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-28: Avoid ΓÇ£__init__.pyΓÇ¥ files in test directories.
tests/fixtures.py
tests/test_auth.py
tests/test_binary.py
tests/test_cli.py
tests/test_defaults.py
tests/test_docs.py
tests/test_downloads.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_output.py
tests/test_sessions.py
tests/test_stream.py
tests/test_unicode.py
tests/test_uploads.py
tests/test_windows.py
tests/utils.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-28: Improve support for 'type/subtype+suffix' mime types in the colors output formatter.
httpie/output/processors/colors.py
tests/test_docs.py
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-28: Cleanup
.travis.yml
tests/test_output.py
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-28: Travis coveralls.
.travis.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-28: Handle HTTP 0.9 in response when formatting version.
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Moved `.directory` from `BaseConfigDict` to `Config`.
httpie/config.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Debug appveyor
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Debug appveyor
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Python 3.4 @ appveyor.
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Debug appveyor
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Modularized output, refactoring
httpie/cli.py
httpie/compat.py
httpie/config.py
httpie/context.py
httpie/core.py
httpie/downloads.py
httpie/input.py
httpie/models.py
httpie/output.py
httpie/output/__init__.py
httpie/output/processors/__init__.py
httpie/output/processors/base.py
httpie/output/processors/colors.py
httpie/output/processors/headers.py
httpie/output/processors/json.py
httpie/output/processors/xml.py
httpie/output/streams.py
httpie/sessions.py
httpie/solarized.py
httpie/utils.py
tests/__init__.py
tests/test_binary.py
tests/test_stream.py
tests/test_windows.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Cleanup
appveyor.yml
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Fix appveyor.yml V.
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Fix appveyor.yml IV.
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Fix appveyor.yml III.
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Fix appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Fix appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-27: Python3.3 Windows CI
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Cleanup
httpie/input.py
tests/fixtures/__init__.py
tests/test_auth.py
tests/test_stream.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Fixed tests.
tests/test_unicode.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Fixed and added tests for --verbose with unicode headers.
httpie/models.py
tests/test_unicode.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: More unicode.
tests/__init__.py
tests/fixtures/__init__.py
tests/fixtures/test.json
tests/fixtures/test.txt
tests/test_sessions.py
tests/test_unicode.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Cleanup
httpie/input.py
tests/test_sessions.py
tests/test_unicode.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated Travis icon URL.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Fixed fixture loading on Windows.
tests/fixtures/__init__.py
tests/test_cli.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Added test_unicode_url_query_arg_item.
tests/test_unicode.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Added support and tests for unicode support in sessions.
httpie/client.py
httpie/plugins/builtin.py
httpie/sessions.py
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Changelog
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: More unicode tests.
tests/fixtures/__init__.py
tests/fixtures/file.txt
tests/fixtures/file2.txt
tests/fixtures/test.bin
tests/fixtures/test.txt
tests/test_uploads.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Added unicode characters to json fixture.
tests/fixtures/test.json

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Python 3 unicode fixes.
httpie/client.py
httpie/models.py
httpie/plugins/builtin.py
httpie/sessions.py
tests/test_defaults.py
tests/test_httpie.py
tests/test_unicode.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Fix tox config.
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Avoid "TypeError: keyword arguments must be strings" on Python 3.3.
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Fix Windows branch.
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Implemented more robust unicode handling.
httpie/client.py
httpie/core.py
httpie/input.py
httpie/models.py
httpie/output.py
httpie/plugins/builtin.py
tests/__init__.py
tests/test_auth.py
tests/test_cli.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_unicode.py
tests/test_uploads.py
tests/test_windows.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Added windows build status icon to README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Disabled test_windows_colorized_output
tests/test_windows.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Run tests in verbose mode.
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Don't used pytest-xdist with setup.py test
appveyor.yml
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated appveyor.yml
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Updated appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-26: Added appveyor.yml
appveyor.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-25: Cleanup
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-25: Cleanup
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-25: Improved session tests.
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-25: Improved auth tests.
tests/__init__.py
tests/test_auth.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-25: Removed unused import.
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-25: Cleanup
README.rst
tests/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-25: Test improvements.
httpie/downloads.py
tests/__init__.py
tests/test_auth.py
tests/test_defaults.py
tests/test_downloads.py
tests/test_sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-25: Removed last dependencies on unittest. All tests are pytest-only.
tests/test_auth.py
tests/test_binary.py
tests/test_cli.py
tests/test_defaults.py
tests/test_docs.py
tests/test_downloads.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_output.py
tests/test_sessions.py
tests/test_stream.py
tests/test_uploads.py
tests/test_windows.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-25: Parametrize test_docs.py.
tests/test_docs.py
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-25: Travis doesn't support Python 3.4 yet.
.travis.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: Parallelized tests using pytest-xdist.
CONTRIBUTING.rst
requirements-dev.txt
setup.py
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: Python 3.4
.travis.yml

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: Added Python 2.6 compatible OrderedDict
httpie/compat.py
httpie/input.py
tests/test_httpie.py
tests/test_output.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: More tests.
httpie/input.py
tests/__init__.py
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: Added docstrings for utilities in `tests.__init__`.
tests/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: Added tests for --debug and --help.
httpie/core.py
tests/__init__.py
tests/test_httpie.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: Added CONTRIBUTING.rst.
CONTRIBUTING.rst
README.rst
requirements-dev.txt
tests/README.rst
tests/test_cli.py
tests/test_docs.py
tests/test_downloads.py
tests/test_httpie.py
tests/test_output.py
tests/test_stream.py
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: Finished pytest migration.
.gitignore
httpie/utils.py
requirements-dev.txt
setup.py
tests/__init__.py
tests/test_downloads.py
tests/test_output.py
tests/test_uploads.py
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: Cleanup
tests/__init__.py
tests/test_auth.py
tests/test_binary.py
tests/test_cli.py
tests/test_defaults.py
tests/test_downloads.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_output.py
tests/test_sessions.py
tests/test_stream.py
tests/test_uploads.py
tests/test_windows.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: Switched to @pytest.mark.skipif.
tests/__init__.py
tests/test_auth.py
tests/test_docs.py
tests/test_exit_status.py
tests/test_windows.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: Moved fixture constants to tests.fixtures.
tests/__init__.py
tests/fixtures/__init__.py
tests/test_binary.py
tests/test_cli.py
tests/test_defaults.py
tests/test_httpie.py
tests/test_sessions.py
tests/test_stream.py
tests/test_uploads.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: Converted all unittest asserts to plain, pytest-powered asserts.
tests/__init__.py
tests/test_auth.py
tests/test_binary.py
tests/test_cli.py
tests/test_defaults.py
tests/test_docs.py
tests/test_downloads.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_output.py
tests/test_sessions.py
tests/test_stream.py
tests/test_uploads.py
tests/test_windows.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-04-24: Refactored tests into smaller modules.
README.rst
httpie/compat.py
httpie/downloads.py
tests/__init__.py
tests/test_auth.py
tests/test_binary.py
tests/test_cli.py
tests/test_defaults.py
tests/test_docs.py
tests/test_downloads.py
tests/test_exit_status.py
tests/test_httpie.py
tests/test_output.py
tests/test_sessions.py
tests/test_stream.py
tests/test_uploads.py
tests/test_windows.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-03-31: Skip ExitStatusTest.test_timeout_exit_status until timeout gets fixed in requests.
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-03-31: Fixed SessionTest.test_session_read_only.
tests/tests.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-03-25: Merge pull request #208 from insyte/master
## Ben Beuchler (insyte@emt-p.org) on 2014-03-24: Update README.rst
README.rst

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-03-18: Merge pull request #172 from unsignedint/master
## Jakub Roztocil (jakub@roztocil.name) on 2014-03-04: Updated installation instructions.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-03-04: Updated installation instructions.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-03-04: Updated installation instructions.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-03-04: Updated installation instructions.
README.rst
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-02-18: Removed Bitdeli badge.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-02-18: Fixed ZeroDivisionError in download summary.
httpie/downloads.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-02-12: Merge pull request #197 from matleh/master
## Matthias Lehmann (ml@qsensei.com) on 2014-02-12: added --cert to CHANGELOG and matleh to AUTHORS
AUTHORS.rst
README.rst

## Matthias Lehmann (ml@qsensei.com) on 2014-02-05: document --cert and --certkey
README.rst

## Matthias Lehmann (ml@qsensei.com) on 2014-02-05: rename -ssl-cert and --ssl-key to --cert and --certkey
httpie/cli.py
httpie/client.py

## Matthias Lehmann (ml@qsensei.com) on 2014-01-29: rename existing_file to readable_file_arg and move to input
httpie/cli.py
httpie/input.py
httpie/utils.py

## Matthias Lehmann (ml@qsensei.com) on 2014-01-29: check --ssl-cert and --ssl-key to be files
httpie/cli.py
httpie/utils.py

## Matthias Lehmann (ml@qsensei.com) on 2014-01-28: add support for client SSL certificate and key
httpie/cli.py
httpie/client.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-01-25: Fixed changelog link.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2014-01-25: v0.8.0
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-01-25: Cleanup
README.rst
httpie/cli.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-01-25: Updated README.
README.rst
httpie/input.py

## Jakub Roztocil (jakub@roztocil.name) on 2014-01-25: Catch UnicodeDecodeError when embedding file via =@ or :=@.
httpie/input.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-01-17: Update README.rst
README.rst

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-01-17: Update README.rst
README.rst

## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-01-08: Merge pull request #191 from solidsnack/wip-no-auth-in-host-header
## Jakub Rozto─ìil (jakub@roztocil.name) on 2014-01-08: Merge pull request #192 from thomasleveil/patch-1
## Thomas L├ëVEIL (thomasleveil@users.noreply.github.com) on 2014-01-07: fix typo
httpie/cli.py

## Jason Dusek (jason.dusek@gmail.com) on 2014-01-06: Expunge user:pass@... from Host header.
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-12-08: Added Bitdeli badge.
README.rst

## Rav Chandra (rav@elysium.co.nz) on 2013-10-16: replace XML processor with ElementTree with custom indentation
httpie/output.py

## Rav Chandra (rav@elysium.co.nz) on 2013-10-16: process XML data before pretty-printing to trim whitespace
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-10-09: Added a link to the httpie-negotiate auth plugin by @ndzou II.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-10-09: Added a link to the httpie-negotiate auth plugin by @ndzou.
README.rst

## Jakub Rozto─ìil (jakub@roztocil.name) on 2013-10-09: Merge pull request #171 from nlf/master
## Nathan LaFreniere (quitlahok@gmail.com) on 2013-10-09: add self to authors, update changelog, and mention shorthand in --help output
AUTHORS.rst
README.rst
httpie/cli.py

## Nathan LaFreniere (quitlahok@gmail.com) on 2013-10-09: tweak readme more
README.rst

## Nathan LaFreniere (quitlahok@gmail.com) on 2013-10-09: tweak readme more
README.rst

## Nathan LaFreniere (quitlahok@gmail.com) on 2013-10-09: tweak readme to show http requests
README.rst

## Nathan LaFreniere (quitlahok@gmail.com) on 2013-10-09: make shorthand parsing more robust, add unit tests and documentation
README.rst
httpie/input.py
tests/tests.py

## Nathan LaFreniere (quitlahok@gmail.com) on 2013-10-08: allow :port style shorthand
httpie/input.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-25: Update --proxy examples to include URLs to work with Requests v2.0.0..
README.rst
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-25: Fixed password prompt.
httpie/input.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-25: Fixed a bytes/str issue for Python 3.
httpie/input.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-24: Allow embeding text (=@) and JSON (:=@) files content into request data fields.
README.rst
httpie/__init__.py
httpie/cli.py
httpie/input.py
tests/fixtures/test.json
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-24: 0.7.1
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-24: Update to requests 2.0.0
README.rst
httpie/models.py
setup.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-24: Removed unused import.
httpie/client.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-24: Cleanup
httpie/client.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-24: Changelog
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-24: 0.7.0
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-24: Merge branch 'master' of github.com:jkbr/httpie
## Jakub Roztocil (jakub@roztocil.name) on 2013-09-24: Improved Content-Disposition parsing for --download mode
README.rst
httpie/downloads.py
tests/tests.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2013-09-23: Merge pull request #167 from matt-hickford/master
## Matt Hickford (matt.hickford@gmail.com) on 2013-09-23: Fix plugins ImportError described at https://github.com/jkbr/httpie/issues/166#issuecomment-24905910
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-22: Improved .netrc example formatting.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-22: Improved .netrc example formatting.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-22: Added link to httpie-oauth.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-09-21: Added support for auth plugins.
README.rst
httpie/__init__.py
httpie/cli.py
httpie/client.py
httpie/core.py
httpie/input.py
httpie/plugins/__init__.py
httpie/plugins/base.py
httpie/plugins/builtin.py
httpie/plugins/manager.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-08-23: Added --ignore-stdin
README.rst
httpie/cli.py
httpie/input.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-08-18: Cleanup
httpie/compat.py
httpie/downloads.py
httpie/models.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-08-10: Improved --help output.
httpie/cli.py
httpie/input.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-08-01: Try to import argparse before adding it to reqs.
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-08-01: README
README.rst
setup.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2013-07-31: Merge pull request #153 from lorin/patch-1
## Lorin Hochstein (lorinh@gmail.com) on 2013-07-31: Augment cookie example in README for multiple cookies
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-07-07: Print error when download is interrupted by server
httpie/core.py
httpie/downloads.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-06-03: `httpless` outputs also response headers by default
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-06-03: README
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-06-03: v0.6.0
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-06-02: Fixed headers tests; Require requests>=1.2.3.
setup.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-06-02: Added XML formatting to CHANGELOG.
AUTHORS.rst
README.rst
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-06-02: Handle unicode when formatting XML.
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-06-02: Merge branch 'master' of git://github.com/jargonjustin/httpie into jargonjustin-master
## Jakub Roztocil (jakub@roztocil.name) on 2013-05-20: Add custom Host example.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-05-14: Fixed download ETA for Python 2.6.
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-05-14: Use Thread instead of Timer for progress reporting.
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-05-14: cleanup
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-05-13: test_download_no_Content_Length
README.rst
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-05-13: Added anonymous sessions (--session=/file/path.json).
README.rst
httpie/cli.py
httpie/client.py
httpie/config.py
httpie/input.py
httpie/sessions.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-05-13: 0.6.0-dev
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-05-13: v0.5.1
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-05-13: Changelog
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-05-13: Changelog
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-05-13: Ignore Content-* and If-* request headers.
README.rst
httpie/client.py
httpie/sessions.py
requirements-dev.txt
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-27: v0.5.0
README.rst
httpie/__init__.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-27: Cleanup
README.rst
httpie/input.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-17: Merge remote-tracking branch 'origin/master'
## Jakub Rozto─ìil (jakub@roztocil.name) on 2013-04-17: Merge pull request #142 from capncodewash/netrc-example
## Graeme West (graeme.west@ncr.com) on 2013-04-17: Added example for .netrc usage (see issue #139 in upstream.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-16: Stop the progres reporter thread on error.
httpie/core.py
httpie/downloads.py
requirements-dev.txt
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-15: Tests
README.rst
httpie/downloads.py
httpie/utils.py
requirements-dev.txt
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-13: Added a simple download test.
httpie/downloads.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-13: Fixed downloads with no Content-Length.
README.rst
httpie/downloads.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Cleanup
README.rst
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Fixed length progress bar.
README.rst
httpie/downloads.py
httpie/utils.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Colorize stderr on Windows.
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: TODOs
httpie/client.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Fixed Content-Type retrieval for Python 3.
httpie/downloads.py
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Fixed tests for Python 2.6.
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Cleanup
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Validate download options before setting up streams.
httpie/input.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Only use Range when already have a partial download.
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Docs fix.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Cleanup
README.rst
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: --download docs (#104).
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Added support for output redirection with --download (#104).
httpie/downloads.py
httpie/input.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Tests
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Used Content-Disposition filename (#104).
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Handle KeyboardInterrupt while --download'ing (#104).
httpie/core.py
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-12: Performance and progress bar improvements.
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-11: Improved progress bar (#104).
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-11: Cleanup
httpie/core.py
httpie/downloads.py
requirements.txt
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-11: Cleanup
README.rst
httpie/downloads.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-11: Added Content-Range parsing tests.
httpie/downloads.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-11: Improved Content-Range parsing.
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-11: Download resume improvements.
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-10: Progress bar update
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-10: Cleanup.
httpie/downloads.py
httpie/utils.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-04-02: --json with no data sets Content-Type as well
httpie/client.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-03-24: Progress on --download.
httpie/core.py
httpie/downloads.py
httpie/humanize.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-03-22: Corrected session info in the README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-03-20: Formatting
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-03-20: Merge pull request #135 from Scorpil/master
## asavchyn (asavchyn@lohika.com) on 2013-03-20: Fixed PyPy cookie updating issue
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-03-07: Handle downloads with no Content-Length.
httpie/core.py
httpie/downloads.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-03-07: Fixed streaming (closes #133)
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-03-03: Fixed unique suffix placement for URLs with a file extension.
httpie/downloads.py
httpie/humanize.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-02-26: Initial --download implementation (#104).
README.rst
httpie/__init__.py
httpie/cli.py
httpie/core.py
httpie/downloads.py
httpie/humanize.py
httpie/input.py
httpie/models.py
httpie/output.py
requirements.txt
tests/tests.py
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2013-02-26: v0.4.1
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-02-26: Removed a reference to the removed `httpie` command
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-02-22: Updated README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-02-22: v0.4.0
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-02-22: Added new logo by @claudiatd :sparkles:
AUTHORS.rst
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2013-02-22: Removed the management command.
README.rst
httpie/cli.py
httpie/manage.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-02-22: .gitignore
.gitignore

## Jakub Roztocil (jakub@roztocil.name) on 2013-02-22: Multiple headers TODO.
httpie/input.py
requirements.txt

## Jakub Roztocil (jakub@roztocil.name) on 2013-01-22: Simplified stored session cookie data.
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-01-22: Session name escaping.
README.rst
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-01-04: Fixing tests for Travis.
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-01-04: Fixing tests for Travis.
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-01-04: Fixing tests for Travis.
httpie/sessions.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-01-04: Fixed request/response session cookies.
README.rst
httpie/sessions.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-01-03: Python 3.3 fixes.
httpie/manage.py
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-01-03: Compatibility with requests v1.0.4 (requests URL params).
httpie/models.py
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-01-03: Added Python 3.3 to tox and travis conf.
.travis.yml
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2013-01-03: Use `urlsplit` instead of `urlparse`.
httpie/cli.py
httpie/compat.py
httpie/config.py
httpie/core.py
httpie/input.py
httpie/models.py
httpie/output.py
httpie/sessions.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2013-01-03: Clean up
README.rst
httpie/sessions.py
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-19: Merge branch 'master' of github.com:jkbr/httpie
## Jakub Roztocil (jakub@roztocil.name) on 2012-12-19: Require Requests v1.0.3.
README.rst
httpie/sessions.py
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-19: Revert: Test Python 3.3 on Travis.
.travis.yml

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-19: Test Python 3.3 on Travis.
.travis.yml

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-19: Requests v1.0: Fixed request body access.
httpie/models.py

## Justin Bonnar (justinbonnar@gmail.com) on 2012-12-17: Pretty print XML
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-17: Requests 1.0: session cookies.
httpie/client.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-17: Merge branch 'master' of github.com:jkbr/httpie
## Jakub Roztocil (jakub@roztocil.name) on 2012-12-17: Requests 1.0: prefetch; default_headers.
httpie/client.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-17: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-11: Session commands.
README.rst
httpie/cli.py
httpie/core.py
httpie/input.py
httpie/manage.py
httpie/models.py
httpie/output.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-05: Improved --check-status + HTTP error + stdout redirect warning.
httpie/core.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-05: Cleanup
httpie/__init__.py
httpie/core.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-05: PEP8
httpie/cli.py
httpie/client.py
httpie/config.py
httpie/input.py
httpie/models.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-05: Fixed `httpie session list`
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-01: Updated session docs.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-01: RST formatting.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-01: Added docs for `httpie`.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-01: Progress on `httpie session *`.
README.rst
httpie/__init__.py
httpie/config.py
httpie/manage.py
httpie/sessions.py
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-01: Typo
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-01: Fixed README typo.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-01: Fixed -j & -v & redirected stdout. Closes #109.
httpie/client.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-01: Added `httpless` to README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-12-01: Clean up.
README.rst
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-11-09: Output stream refactoring.
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-11-08: Updated CHANGELOG (#100).
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-11-08: Added support for credentials in URL.
README.rst
httpie/input.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-24: Added --no-option's and made args more config-friendly.
README.rst
httpie/cli.py
httpie/input.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-24: Improved README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-21: 0.3.0
README.rst
httpie/__init__.py
httpie/cli.py
httpie/core.py
httpie/sessions.py
setup.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-21: Allow output redirection on Windows.
README.rst
httpie/input.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-17: Documented config.
README.rst
httpie/config.py
httpie/core.py
httpie/input.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-17: Added tests for sessions.
httpie/cli.py
httpie/client.py
httpie/config.py
httpie/core.py
httpie/models.py
httpie/sessions.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-17: Use the `HTTPIE_CONFIG_DIR` environment variable.
httpie/config.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-17: Added configuration file.
httpie/client.py
httpie/config.py
httpie/core.py
httpie/input.py
httpie/models.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-17: Renamed --session-read to --session-read-only.
README.rst
httpie/cli.py
httpie/client.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-07: Cleanup.
httpie/client.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-07: Added `--session-read` for read-only sessions.
README.rst
httpie/cli.py
httpie/client.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-07: Renamed --allow-redirects to --follow.
README.rst
httpie/cli.py
httpie/client.py
httpie/core.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-21: Cleanup
httpie/cli.py
httpie/client.py
httpie/input.py
httpie/models.py
httpie/output.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-09-04: Merge pull request #90 from simonbuchan/898408c20cfab130699cee3bedbae1ad4a1c69b1
## Simon Buchan (simon.buchan.nz@gmail.com) on 2012-09-04: Fix sessions for Windows
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-19: Sessions are now host-bound.
README.rst
httpie/cli.py
httpie/manage.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-18: README
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-18: JSON session data, `httpie' management command.
README.rst
httpie/cli.py
httpie/client.py
httpie/input.py
httpie/manage.py
httpie/output.py
httpie/sessions.py
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-18: Grouped arguments for a more user-friendly --help.
README.rst
httpie/cli.py
httpie/input.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-18: Include data directory location with --debug.
httpie/cli.py
httpie/core.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-18: Use %APPDATA% for data on Windows.
httpie/config.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-18: Fixed Solarized style unavailable on Windows.
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-17: Updated README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-17: Updated README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-17: Updated README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-17: Added initial support for persistent sessions.
## Jakub Roztocil (jakub@roztocil.name) on 2012-08-17: Added initial support for persistent sessions.
README.rst
httpie/cli.py
httpie/client.py
httpie/config.py
httpie/core.py
httpie/sessions.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-17: Semver-compatible versioning.
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-17: Unified output processing options under --pretty.
README.rst
httpie/cli.py
httpie/input.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-17: Fixed colorized output on Windows with Python 3.
README.rst
httpie/core.py
httpie/models.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-16: Removed non-ASCII characters from README (closes #85).
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-16: Fixed readme decoding.
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-16: Revert "Iter body lines to avoid binary false positives."
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-13: Iter body lines to avoid binary false positives.
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-12: Updated changelog.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-10: Use CRLF for headers in the output.
httpie/models.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-09: Improved examples.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-07: Added exit status for timed-out requests.
README.rst
httpie/__init__.py
httpie/cli.py
httpie/core.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-07: Added README reStructuredText validation.
README.rst
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-07: Added --colors and --format.
README.rst
httpie/cli.py
httpie/input.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-07: Documented --verify.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-07: Skip tests with redirects on Requests 0.13.6.
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-07: Version fix.
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-07: Improved --debug.
httpie/__init__.py
httpie/cli.py
httpie/core.py
httpie/input.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-07: Pre-process README.rst so that PyPi renders it.
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-07: Added proxy docs.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-07: v0.2.8dev
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-07: v0.2.7
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-07: Compatibility with Requests 0.13.6.
README.rst
httpie/core.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-06: Extended README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-06: Set JSON Content-Type only with data even with -j.
httpie/core.py
httpie/models.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-04: Added exit status constants, cleaned up main().
httpie/__init__.py
httpie/core.py
httpie/input.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-04: Improved password prompt.
httpie/core.py
httpie/input.py
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-04: Changelog, typos
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-03: Streamed terminal output
.gitignore
README.rst
httpie/__init__.py
httpie/cli.py
httpie/core.py
httpie/models.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-03: Sort headers by name when prettifying.
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-02: Fixed error handling.
httpie/core.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-01: Cleanup, CHANGELOG
README.rst
httpie/core.py
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-01: Take advantage of streaming.
README.rst
httpie/core.py
httpie/input.py
httpie/models.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-01: Don't fetch the response body unless needed.
README.rst
httpie/core.py
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-01: Fallback to media subtype if the type is uknown.
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-08-01: Added tests for binary request data.
httpie/core.py
httpie/input.py
httpie/models.py
tests/fixtures/file.bin
tests/fixtures/file.txt
tests/fixtures/file2.txt
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-30: cleanup
README.rst
httpie.png
httpie/httpie.png
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-30: Syntax-highlighting for examples in the README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-30: Syntax-highlighting for examples in the README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-30: Updated screenshot.
httpie/httpie.png

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-30: Updated screenshot.
httpie/httpie.png

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-30: Updated screenshot.
httpie/httpie.png

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-30: Updated screenshot.
httpie.png

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-30: Updated solarized and switched to Solarized256Style.
httpie/output.py
httpie/solarized.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-30: Added AUTHORS
AUTHORS.rst
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-30: Revorked output
README.rst
httpie/cli.py
httpie/core.py
httpie/input.py
httpie/models.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-29: Better error messages.
httpie/input.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-29: Consistent request-response separators.
httpie/core.py
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-29: Validate "file fields (name@/path) require --form / -f".
httpie/input.py
httpie/models.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-29: Removed redundant decode/encode.
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-28: Send filenames with multipart/form-data file uploads.
README.rst
httpie/input.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-28: Fixed typos.
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-28: Fixed multipart requests output; binary support.
README.rst
httpie/cli.py
httpie/core.py
httpie/input.py
httpie/models.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-27: Default to https:// if invoked as `https'.
.gitignore
README.rst
httpie/__init__.py
httpie/core.py
httpie/models.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-26: v0.2.7dev
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-26: v0.2.6
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-26: Added docstrings, refactored input.
README.rst
httpie/__main__.py
httpie/cli.py
httpie/core.py
httpie/input.py
httpie/models.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-26: Mention necessary quoting with `:=`. #77
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-26: Improved error messages.
httpie/cli.py
httpie/cliparse.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-26: Clean-up
.travis.yml
README.rst
httpie/cliparse.py
httpie/core.py
httpie/models.py
httpie/output.py
setup.py
tests/tests.py
tox.ini

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-25: Ensure that full querystring is printent with -v.
httpie/cliparse.py
httpie/models.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-24: Fixed RST formatting.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-24: Short option for --headers is now -h.
README.rst
httpie/cli.py
httpie/cliparse.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-24: Allow multiple fields with the same name.
README.rst
httpie/cli.py
httpie/cliparse.py
httpie/core.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-24: Switched to "==" a the separator for URL params.
README.rst
httpie/cli.py
httpie/cliparse.py
httpie/core.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-24: Updated changelog.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-24: Replaced --ignore-http-status with --check-status.
README.rst
httpie/cli.py
httpie/core.py
httpie/models.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-23: Fixed tests.
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-23: Added exit codes for HTTP 3xx, 4xx, 5xx (3, 4, 5).
README.rst
httpie/__main__.py
httpie/cli.py
httpie/core.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-21: Fixed colorama initialization (#36).
httpie/core.py
httpie/models.py
httpie/output.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-21: Use local `httpbin` for all tests if available.
README.rst
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-21: Undebug
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-21: Fixed tests.
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-21: Added `models.Environment()`.
httpie/__main__.py
httpie/cli.py
httpie/cliparse.py
httpie/core.py
httpie/httpmessage.py
httpie/models.py
httpie/output.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-20: Updated flags in README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-20: Changed default --print to "b" if stdout piped.
README.rst
httpie/__main__.py
httpie/cli.py
httpie/cliparse.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-20: Updated installation instructions.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-20: Improved highlighting of HTTP headers.
README.rst
httpie/pretty.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-19: Updated changelog; added stable version README link.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-19: Merge pull request #72 from jakebasile/issue-61
## Jake Basile (jakebasile@me.com) on 2012-07-18: Updated documentation for query string params.
README.rst
httpie/cli.py

## Jake Basile (jakebasile@me.com) on 2012-07-18: Added a bit of testing for the new query string parameters.
tests/tests.py

## Jake Basile (jakebasile@me.com) on 2012-07-18: Added the ability to pass query string parameters.
httpie/__main__.py
httpie/cli.py
httpie/cliparse.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: Clean up.
README.rst
httpie/cli.py
httpie/cliparse.py
httpie/pretty.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: Updated changelog.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: Added support for terminal colors under Windows.
httpie/__main__.py
httpie/pretty.py
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: README fixes.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: 0.2.6dev
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: 0.2.5 (bugfixes)
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: Fixed tests exist status.
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: Python 3 fixes.
httpie/pretty.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: Fixed AttributeError in Content-Type vendor removal.
httpie/pretty.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: Fixed accidentally remove __licence__.
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: 0.2.5dev
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: 0.2.5dev
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: 0.2.4 (bad upload of 0.2.3 to pypi).
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: Merge branch 'master' of github.com:jkbr/httpie
## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: 0.2.4dev
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: 0.2.3
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-16: Merge pull request #69 from jokull/master
## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: Add a note on pretty JSON and unicode to changelog
README.rst

## Oleg Churkin (bahusoff@gmail.com) on 2012-07-15: Added test case to verify unicode output
tests/tests.py

## Oleg Churkin (oleg.churkin@inn.ru) on 2012-07-12: Now non-ascii symbols displayed correctly in the output (not as escape sequences).
httpie/pretty.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-17: Better wording.
README.rst
httpie/cli.py
httpie/cliparse.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-16: Allow stdin data with password prompt; added tests
README.rst
httpie/cli.py
httpie/cliparse.py
tests/tests.py

## Ismail Badawi (isbadawi@gmail.com) on 2012-07-16: Update README with new --auth behavior.
README.rst

## Ismail Badawi (isbadawi@gmail.com) on 2012-07-16: Have --auth prompt for password if omitted.
httpie/cli.py
httpie/cliparse.py

## Jo╠êkull So╠ülberg Au├░unsson (jokull@solberg.is) on 2012-07-14: Simplify vendor extension content-types since they are most likely lexable
httpie/pretty.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-13: Merge pull request #68 from cemaleker/master
## Cemal Eker (cemaleker@gmail.com) on 2012-07-14: Added omitted query string data to request headers.
httpie/httpmessage.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-11: Merge pull request #65 from simono/patch-1
## Simon Olofsson (simon@olofsson.de) on 2012-07-11: Update README.rst and add links to Ubuntu and Debian Packages.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-07-04: Fixed Content-Type for requests with no data.
httpie/__main__.py
httpie/cliparse.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-29: Added support for request payload from a filepath
README.rst
httpie/__main__.py
httpie/cli.py
httpie/cliparse.py
tests/file2.txt
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-25: Added more examples.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-24: 0.2.3dev
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-24: 0.2.2
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-24: Impreved tests.
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-24: Tests, docs, clean-up.
.travis.yml
README.rst
httpie/cli.py
httpie/cliparse.py
setup.py
tests/test_cliparse.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-24: Default to POST also when stdin redirected.
httpie/__main__.py
httpie/cli.py
httpie/cliparse.py
tests/test_cliparse.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-23: Replaced `mock.Mock` with `argparse.Namespace` to reduce deps.
tests/test_cliparse.py

## Vladimir Berkutov (dair.targ@gmail.com) on 2012-06-17: Issue #54 Method suggestion proposal
httpie/cliparse.py

## Vladimir Berkutov (dair.targ@gmail.com) on 2012-06-17: Issue #54 Method suggestion proposal
README.rst
httpie/cli.py
httpie/cliparse.py

## Vladimir Berkutov (dair.targ@gmail.com) on 2012-06-17: Issue #54 Method suggestion proposal
README.rst
httpie/__main__.py
httpie/cli.py
httpie/cliparse.py
tests/test_cliparse.py
tests/tests.py

## Vladimir Berkutov (dair.targ@gmail.com) on 2012-06-16: Issue #54 Method suggestion proposal
httpie/__main__.py
httpie/cli.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-15: README improvements.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-15: Added a Contribute section to README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-15: Fixed --verbose --form.
httpie/httpmessage.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-13: Merge pull request #51 from msabramo/testing
## Marc Abramowitz (marc@marc-abramowitz.com) on 2012-06-13: Add "pypy" to .travis.yml
.travis.yml

## Marc Abramowitz (marc@marc-abramowitz.com) on 2012-06-04: Add tox.ini for tox (http://tox.testrun.org/)
.gitignore
tox.ini

## Marc Abramowitz (marc@marc-abramowitz.com) on 2012-06-04: Fix path to tests.py in setup.py to make `python setup.py test` work
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-13: Bump version to 0.2.2dev.
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-13: 0.2.1
README.rst
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-13: Ensured a new line after the request message in the output.
httpie/__main__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-13: Made --verbose work also with requests<0.12.1.
httpie/httpmessage.py
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-13: Version bump to 0.2.1dev.
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-06-13: Merge pull request #50 from dair-targ/master
## Jakub Roztocil (jakub@roztocil.name) on 2012-06-13: Merge pull request #45 from gandaro/pygments-lexers
## Vladimir Berkutov (dair.targ@gmail.com) on 2012-06-02: --verbose flag was not working. Here is bugfix.
httpie/httpmessage.py

## Jakob Kramer (jakob.kramer@gmx.de) on 2012-04-28: PEP-8
httpie/cliparse.py
httpie/pretty.py
httpie/solarized.py

## Jakob Kramer (jakob.kramer@gmx.de) on 2012-04-28: use PrettyHttp class; working --headers and --body
httpie/__main__.py
httpie/httpmessage.py
httpie/pretty.py

## Jakob Kramer (jakob.kramer@gmx.de) on 2012-04-26: Use the full capability of HttpLexer
httpie/__main__.py
httpie/httpmessage.py
httpie/pretty.py

## Jakob Kramer (jakob.kramer@gmx.de) on 2012-04-26: Use the Pygments HTTP and JSON lexers
httpie/pretty.py
httpie/pygson.py
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-04-25: Fixed classifiers in setup.py.
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-04-25: Updated README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-04-25: 0.2.0
httpie/__init__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-04-25: Updated README and docs.
README.rst
httpie/__main__.py
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-04-25: Major clean-up and refactoring.
httpie/__main__.py
httpie/cli.py
httpie/cliparse.py
httpie/httpmessage.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-04-25: Fixed several unicode-related issues
httpie/__main__.py
httpie/cli.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-04-24: Merge pull request #44 from jakebasile/master
## Jake Basile (jakebasile@me.com) on 2012-04-18: Fixed escaping for long separators.
httpie/cli.py
tests/tests.py

## Jake Basile (jakebasile@me.com) on 2012-04-16: Removed accidentally included old funky code.
httpie/cli.py

## Jake Basile (jakebasile@me.com) on 2012-04-16: Added ability to escape parameters... except for the := ones.
httpie/cli.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-04-14: Merge pull request #43 from jakebasile/master
## Jake Basile (jakebasile@me.com) on 2012-04-14: -j/--json now adds "Accept": "application/json" to GET requests if no previous Accept header exists.
httpie/__main__.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-04-11: Lowered the minimum version of requests required
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-04-11: Added --auth-type and tests for basic/digest auth.
httpie/__main__.py
httpie/cli.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-04-11: Merge branch 'digest-auth' of https://github.com/dshafik/httpie into dshafik-digest-auth
## Jakub Roztocil (jakub@roztocil.name) on 2012-04-11: Refactored @mmb's fix to --verify; updated docs.
README.rst
httpie/__main__.py
httpie/cli.py

## Matthew M. Boedicker (matthewm@boedicker.org) on 2012-04-05: make --verify no command line argument work
httpie/__main__.py

## Davey Shafik (me@daveyshafik.com) on 2012-03-22: Add support for Digest authentication
httpie/__main__.py
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-15: Python 3 fixes (travis config).
.travis.yml

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-15: Python 3 fixes.
.travis.yml
README.rst
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-15: Added `argparse` for Python 3.1.
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-15: Added Python 3 support
.travis.yml
README.rst
httpie/__main__.py
httpie/pretty.py
setup.py
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-14: Improved README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-14: Improved request formatting.
httpie/__main__.py
httpie/pretty.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-14: Assume "/" as the Request-URI for printing when none present.
httpie/__main__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-14: Fixed tests.
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-14: Added file upload support
.travis.yml
README.rst
httpie/__main__.py
httpie/cli.py
tests/file.txt
tests/tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-14: Added a --verbose / -v flag
httpie/cli.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-14: Made sure request Host is correct when printing.
httpie/__main__.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-14: Added a "New in development version" link.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-14: Added the option to print the request
LICENSE
README.rst
httpie/__init__.py
httpie/__main__.py
httpie/cli.py
httpie/pretty.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-13: Added better JSON highlighting
httpie/pretty.py
httpie/pygson.py

## Praful Mathur (praful.mathur@gmail.com) on 2012-03-13: Merge remote-tracking branch 'upstream/master'
## Jakub Roztocil (jakub@roztocil.name) on 2012-03-09: Added BSD license text
LICENSE
MANIFEST.in

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-09: Added BSD license text
LICENSE
MANIFEST.in

## Praful Mathur (praful.mathur@gmail.com) on 2012-03-05: Added proper JSON highlighting
httpie/pretty.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-05: Merge pull request #24 from faulkner/fix-packaging
## Chris Faulkner (thefaulkner@gmail.com) on 2012-03-04: Update references to moved README.
MANIFEST.in
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-05: Update README.rst
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-05: Updated README.
README.rst

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-04: Added support for more 256 color terminals.
httpie/pretty.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-04: Added a link to contributors on GitHub to README.
README.md

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-04: Merge pull request #21 from laurentb/packaging
## Laurent Bachelier (laurent@bachelier.name) on 2012-03-04: One argument per line
setup.py

## Laurent Bachelier (laurent@bachelier.name) on 2012-03-04: Include README.md in the source tarball
MANIFEST.in
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-04: Updated screenshot.
httpie.png

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Fixed IOError in setup.py.
README.md
httpie/__init__.py
setup.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: v0.1.5
README.md
httpie/__init__.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Corrected line breaks in the output.
httpie/__main__.py
httpie/pretty.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Fixed --pretty tests.
tests.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Fixed tests II.
tests.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Fixed tests.
.travis.yml
tests.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Updated travis config.
.travis.yml
README.md

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Added travis-ci configuration.
.travis.yml
httpie/__main__.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Fixed tests for Python 2.6.
tests.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Updated README.
README.md

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Added argument parsing tests.
README.md
tests.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Added --version.
httpie/cli.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Factored out CLI parsing.
httpie/__main__.py
httpie/cli.py
httpie/pretty.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Improved setup.py
setup.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Merge branch 'main-module-convention' of https://github.com/gandaro/httpie into gandaro-main-module-convention
## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Fixed README.
README.md

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Added `field-name:=raw-json` Closes #14
README.md
httpie/httpie.py
setup.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Updated readme (--flags).
README.md

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-04: Refactored --pretty and added tests.  #16
httpie/httpie.py
tests.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-03: Merge pull request #16 from tictactix/master
## Jakub Roztocil (jakub@roztocil.name) on 2012-03-03: Merge pull request #19 from faulkner/fix-readme
## Jakub Roztocil (jakub@roztocil.name) on 2012-03-03: Merge pull request #17 from faulkner/fix-redirects
## Chris Faulkner (thefaulkner@gmail.com) on 2012-03-03: Correct usage string in README.
README.md

## Chris Faulkner (thefaulkner@gmail.com) on 2012-03-03: Typo.
README.md

## Chris Faulkner (thefaulkner@gmail.com) on 2012-03-03: Pass allow_redirects to request so --allow-redirects works.
httpie/httpie.py

## Praful Mathur (praful.mathur@gmail.com) on 2012-03-02: Force pretty printing (ignore last commit; stupid undo mistake)
httpie/httpie.py

## Praful Mathur (praful.mathur@gmail.com) on 2012-03-02: Added forcing pretty printing for piping purposes.
httpie/httpie.py

## Jakob Kramer (jakob.kramer@gmx.de) on 2012-03-02: use the __main__ submodule convention to make it possible to use `python -m httpie`
httpie/__main__.py
setup.py
tests.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-02: Fixed a missing line between headers and body.
httpie/httpie.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-02: Fixed a `UnicodeError` in Python 2.6.
httpie/httpie.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-02: Added first tests.
README.md
httpie/httpie.py
tests.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-02: Added --style Closes #6. Thanks, @iromli.
## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-03-01: Made argparse required only for Python < 2.7.
setup.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-03-01: Merge pull request #12 from tomekwojcik/master
## Jakub Roztocil (jakub@roztocil.name) on 2012-03-01: Merge pull request #10 from marblar/osx
## Tomek Wo╠üjcik (labs@tomekwojcik.pl) on 2012-03-01: * Added argparse to install_requires.
setup.py

## Mark Larus (larusm@kenyon.edu) on 2012-02-29: Support for terminals not using 256 color
httpie/pretty.py

## Isman Firmansyah (isman@sixreps.com) on 2012-02-29: remove unnecessary partial call
httpie/pretty.py

## Isman Firmansyah (isman@sixreps.com) on 2012-02-29: added support to use other pygments styles, falback to solarized
httpie/httpie.py
httpie/pretty.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-28: 0.1.4
httpie/__init__.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-28: Do not assume UTF-8.
httpie/httpie.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-02-28: Merge pull request #2 from flashingpumpkin/master
## Alen Mujezinovic (flashingpumpkin@gmail.com) on 2012-02-28: Revert "Not all web servers return UTF-8 and will crash httpie when decoding the response"
httpie/httpie.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-28: Fixed __version__ and __doc__ import. Thanks, @FND.
httpie/httpie.py

## Alen Mujezinovic (flashingpumpkin@gmail.com) on 2012-02-28: Not all web servers return UTF-8 and will crash httpie when decoding the response
httpie/httpie.py

## Alen Mujezinovic (flashingpumpkin@gmail.com) on 2012-02-28: Removed the lists in favour of generators
httpie/httpie.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-28: Merge branch 'master' of github.com:jkbr/httpie
## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-28: Fixed setup.py to work without having pygments already installed. Closes #1.
httpie/__init__.py
httpie/httpie.py
setup.py

## Alen Mujezinovic (flashingpumpkin@gmail.com) on 2012-02-28: Syntax error fix
httpie/httpie.py

## Jakub Roztocil (jakub@roztocil.name) on 2012-02-27: typo
README.md

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-27: Renamed the CLI tool `http`.
README.md
httpie.png
httpie/httpie.py
setup.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-26: Added Solarized color scheme for Pygments by @gthank.
httpie/httpie.py
httpie/solarized.py
setup.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-26: Added error handling.
httpie/httpie.py
httpie/pretty.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-26: Fixed header formatting.
httpie/httpie.py
httpie/pretty.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-26: Added --headers and --body to limit the output.
httpie/httpie.py
httpie/pretty.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2012-02-25: Update README.md
README.md

## Jakub Rozto─ìil (jakub@roztocil.name) on 2012-02-25: Fixed README.
README.md

## Jakub Rozto─ìil (jakub@roztocil.name) on 2012-02-25: Fixed README
README.md

## Jakub Rozto─ìil (jakub@roztocil.name) on 2012-02-25: Update README.md
README.md

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-25: Fixed a typo.
httpie/httpie.py
setup.py

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-25: Merge branch 'master' of github.com:jkbr/httpie
## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-25: Fixed a typo.
httpie/httpie.py

## Jakub Rozto─ìil (jakub@roztocil.name) on 2012-02-25: Update README.md
README.md

## Jakub Rozto─ìil (jakub@roztocil.name) on 2012-02-25: Update README.md
README.md

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-25: Updated README.
README.md

## Jakub Roztoc╠îil (jakub@roztocil.name) on 2012-02-25: Initial commit.
.gitignore
README.md
httpie.png
httpie/__init__.py
httpie/httpie.py
httpie/pretty.py
setup.py
