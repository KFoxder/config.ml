# 0.0.3 

* Refactored expression evaluation – thanks @gpetiot :clap:
* Support conditionally disabling match cases, function branches, module structure and signature items – thank @kfoxder :sparkles:
* Updated cookbook with more examples
* Improvements on nix setup – thanks @metame :rainbow:

# 0.0.2

* Fix single var configuration failing – thanks @metame 👏 
* Support conditionally disabling all structure-items
* Support conditionally disabling variant constructors and record fields
* Add better docs for the Config language, and a small cookbook
* Support `cfg` and `config` for use in Melange v3 and future version

# 0.0.1

Initial release with support for:

* Not, Any, and All expressions in the boolean language
* Checking for environment variables
* Providing `target_os`, `target_arch`, and `target_env`
* Support disabling module expressions 
* Supports disabling entire modules with a single top-level annotation
