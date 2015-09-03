# Kreta VCS Bundle
> VCS bundle of Kreta: modern project manager for software development.

[![Build Status](https://travis-ci.org/kreta-plugins/VCSBundle.svg?branch=master)](https://travis-ci.org/kreta-plugins/VCSBundle)
[![Coverage Status](https://img.shields.io/coveralls/kreta-plugins/VCSBundle.svg)](https://coveralls.io/r/kreta-plugins/VCSBundle)
[![Scrutinizer Code Quality](https://scrutinizer-ci.com/g/kreta-plugins/VCSBundle/badges/quality-score.png?b=master)](https://scrutinizer-ci.com/g/kreta-plugins/VCSBundle/?branch=master)
[![HHVM Status](http://hhvm.h4cc.de/badge/kreta/vcs-bundle.svg)](http://hhvm.h4cc.de/package/kreta/vcs-bundle)
[![Total Downloads](https://poser.pugx.org/kreta/vcs-bundle/downloads)](https://packagist.org/packages/kreta/vcs-bundle)

[![Latest Stable Version](https://poser.pugx.org/kreta/vcs-bundle/v/stable.svg)](https://packagist.org/packages/kreta/vcs-bundle)
[![Latest Unstable Version](https://poser.pugx.org/kreta/vcs-bundle/v/unstable.svg)](https://packagist.org/packages/kreta/vcs-bundle)

Tests
-----

This bundle is completely tested by **[PHPSpec][1], SpecBDD framework for PHP**.

Because you want to contribute or simply because you want to throw the tests, you have to type the following command
in your terminal.

    $ bin/phpspec run -fpretty

>*Depends the location of the `bin` directory (sometimes in the root dir; sometimes in the `/vendor` dir) the way that
works every time is to use the absolute path of the binary `vendor/phpspec/phpspec/bin/phpspec`*

Contributing
------------

This bundle follows PHP coding standards, so pull requests must pass PHP Code Sniffer and PHP Mess Detector
checks. In the root directory of this project you have the **custom rulesets** ([ruleset.xml]() for PHPCS and
[phpmd.xml]() for PHPMD).

There is also a policy for contributing to this project. Pull requests must
be explained step by step to make the review process easy in order to
accept and merge them. New methods or code improvements must come paired with [PHPSpec][1] tests.

If you would like to contribute it is a good point to follow Symfony contribution standards,
so please read the [Contributing Code][2] in the project
documentation. If you are submitting a pull request, please follow the guidelines
in the [Submitting a Patch][3] section and use the [Pull Request Template][4].

If you have any doubt or maybe you want to share some opinion, you can use our **Gitter chat**.
[![Gitter](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/kreta/kreta?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

[1]: http://www.phpspec.net/
[2]: http://symfony.com/doc/current/contributing/code/index.html
[3]: http://symfony.com/doc/current/contributing/code/patches.html#check-list
[4]: http://symfony.com/doc/current/contributing/code/patches.html#make-a-pull-request

Credits
-------
Kreta Core Bundle is created by:
>
**@benatespina** - [benatespina@gmail.com](mailto:benatespina@gmail.com)<br/>
**@gorkalaucirica** - [gorka.lauzirika@gmail.com](mailto:gorka.lauzirika@gmail.com)

Licensing Options
-----------------
[![License](https://poser.pugx.org/kreta/vcs-bundle/license.svg)](https://github.com/kreta/kreta-plugins/blob/master/LICENSE)
