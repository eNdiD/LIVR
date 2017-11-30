![LIVR logo](assets/logo.png)

# Language Independent Validation Rules \(v2.0\)

## Validator meets the following requirements:

1. Rules are declarative and language independent
2. Any number of rules for each field
3. Validator should return together errors for all fields
4. Exclude all fields that do not have validation rules described
5. Possibility to validate complex hierarchical structures
6. Easy to describe and understand validation
7. Returns understandable error codes \(neither error messages nor numeric codes\)
8. Easy to implement own rules \(usually you will have several in every project\)
9. Rules should be able to change results output \("trim", "nested\_object", for example\)
10. Multipurpose \(user input validation, configs validation, contracts programming etc\)
11. Unicode support

## Try online

* [Online JavaScript playground](http://webbylab.github.io/livr-playground/)
* [Online multi-language playground](http://livr-multi-playground.webbylab.com/)


## Existing implemenations

<div class="langContainer">
    <div class="langItem">
        <a href="https://github.com/koorchik/js-validator-livr">
            <img src="assets/languages/js.jpg">
        </a>
        <div class="textBlock">
            <a href="https://github.com/koorchik/js-validator-livr">
                JavaScript (LIVR 2.0)
            </a><br>
            available at
            <a href="https://www.npmjs.com/package/livr">
                npm,
            </a>maintainer @koorchik
        </div>
    </div>
    <div class="langItem">
        <a href="https://github.com/koorchik/Validator-LIVR">
            <img src="assets/languages/perl.jpg">
        </a>
        <div class="textBlock">
            <a href="https://github.com/koorchik/Validator-LIVR">
                Perl (LIVR 2.0)
            </a><br>
            available at
            <a href="https://metacpan.org/pod/Validator::LIVR">
                CPAN,
            </a>maintainer @koorchik
        </div>
    </div>
    <div class="langItem">
        <a href="https://github.com/WebbyLab/php-validator-livr">
            <img src="assets/languages/php.png">
        </a>
        <div class="textBlock">
            <a href="https://github.com/WebbyLab/php-validator-livr">
                PHP (LIVR 2.0)
            </a><br>
            available at
            <a href="https://packagist.org/packages/validator/livr">
                packagist,
            </a>maintainer @WebbyLab
        </div>
    </div>
    <div class="langItem">
        <a href="https://github.com/asholok/python-validator-livr">
            <img src="assets/languages/python.png">
        </a>
        <div class="textBlock">
            <a href="https://github.com/asholok/python-validator-livr">
                Python (LIVR 2.0)
            </a><br>
            available at
            <a href="https://pypi.python.org/pypi/LIVR">
                pypi,
            </a>maintainer @asholok
        </div>
    </div>
    <div class="langItem">
        <a href="https://github.com/Prots/olifer">
            <img src="assets/languages/erlang.png">
        </a>
        <div class="textBlock">
            <a href="https://github.com/Prots/olifer">
                Erlang (LIVR 2.0),
            </a><br>
            maintainer @koorchik
        </div>
    </div>
    <div class="langItem">
        <a href="https://github.com/vlbaluk/java-validator-livr">
            <img src="assets/languages/java.png">
        </a>
        <div class="textBlock">
            <a href="https://github.com/vlbaluk/java-validator-livr">
                Java (LIVR 2.0),
            </a><br>
            maintainer @vlbaluk
        </div>
    </div>
    <div class="langItem">
        <a href="https://github.com/maktwin/ruby-validator-livr">
            <img src="assets/languages/ruby.png">
        </a>
        <div class="textBlock">
            <a href="https://github.com/maktwin/ruby-validator-livr">
                Ruby (LIVR 0.4, previous version),
            </a><br>
            maintainer @maktwin
        </div>
    </div>
</div>



_Latest LIVR version is 2.0_  
_Previous LIVR version is 0.4_

## Documentation

* [Introduction](gitbook/introduction.md)
* [Validation Rules](gitbook/validation-rules.md)
* [Rules aliasing](gitbook/rules-aliasing.md)
* [How to contribute](gitbook/how-to-contribute.md)
* [Changes](gitbook/changes.md)
* [License](gitbook/license-and-copyright.md)