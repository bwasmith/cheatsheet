# Secure Password Creation

## Command
- ```echo -n @ && cat /dev/urandom | env LC_CTYPE=C tr -dc [:alumn:] | head -c 15 && echo``` - this one gets zsh errors
- ```cat /dev/urandom | env LC_CTYPE=C tr -dc a-zA-Z0-9 | head -c 14 && echo``` - this one works better
