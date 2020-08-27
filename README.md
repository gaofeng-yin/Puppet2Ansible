Puppet and Ansible are very robust tools, the first manages settings and the second orchestra settings and services. Both work differently, with the requirements of different resources and complexity at different level. Puppet uses its own declarative language (also called domain-specific language, or DSL) and Ansible use YAML syntax. In order to automate the passage of Puppet modules and rules to Ansible roles a translation processor will be required, software elected to this function is the ELI, which translates resources from module into plays of role while maintaining the original module function.  In the translation process a file with Puppet declarative code is introduced as input and the translation processor checks the grammatical expressions and regular expressions, in the end generates an output with the minutely translated expressions. Later these roles are integrated into an web frontend AWX that provides to the DevOps access to the latest features, with a more friendly interface and dashboard to provide an overview of task executions, failures and successes