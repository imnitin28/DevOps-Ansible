Ansible is an IT automation tools. It helps in,
    -   Provisioning
    -   Deployment
    -   CI/CD

Architecture:

Installation:
    Prerequisite:
        Python
    Install pip
    install boto
    Install Ansible

YAML Basics:
    Main building blocks of ansible,
        -   Scalar
        -   Lists
        -   Dictionary
    
## Jinja - A python template engine
It enables dynamic expressions and access to variables

{% ... %} for Statements
{{ ... }} for Expressions to print the template output
{# ... #} for Comments, it is not included in template output
# ... ## for Line statements

e.g
{{test}}  -> abc                    | Variables
{{"abc"}} -> "abc"                  | String
{{1+1}}   -> 2                      | Number
{{[1,2,3,4,5]}} -> ] [1,2,3,4,5]    | List

{{{'dict':'of','key':'and','value':'pairs'}}} -> {'dict':'of','key':'and','value':'pairs'} | Dictionary

## Types of Variables in Ansible

## Create EC2 using Modules
ansible-galaxy collection install amazon.aws
