# Yarn

Install Yarn

    brew install yarn

Switch yarn to specific version / latest version (yarn 1.x)

    yarn policies set-version <version>
    yarn policies set-version

Switch yarn to specific version / latest version (yarn 2.x)

    yarn set version <version>
    yarn set version latest

## Information

Show yarn version and help

    yarn -v
    yarn help

Show information for a package

    yarn info <package>

Show why a package was installed

    yarn why <package>

## List

List installed packages (local / global)

    yarn list
    yarn global list

List only top level global packages

    yarn list --depth=0
    yarn global list --depth=0

List packages that match pattern

    yarn list --pattern <string>

## Init
