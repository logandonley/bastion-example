# bastion-example

Example bastion host. More instructions will come later.

To setup, modify the files in the inventory directory to match your needs.

Then run `ansible-playbook -i inventory bastion.yml`.

This expects the host to have a Fedora server already configured and a user with ssh (key-based) access.

This has only been tested on [Fedora Server 28][1].



[1]: https://getfedora.org/en/server/
