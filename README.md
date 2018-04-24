# CTF-buf1
Binary challenge 1 for Beginner CTF @ Nerdlab

If you want to solve this locally, compile with:

gcc -g -fno-stack-protector -z execstack -o buf buf.c

Contestants will have to solve this without sourcecode.

This will be ran as a service on a server, so contestant won't  have access to a bash prompt.
If you're solving this locally, you can only make use of the program, and not the bash shell it's running in.

Retrieve the contents of the secret flag file somewhere in the filesystem using the only the compiled binary provided.
