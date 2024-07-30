# Metadata

* Working group name: Secure Shell
* Working group acronym: SSH
* Mailing list: ssh@ietf.org

[ Open question: see
[issue #1](https://github.com/DavidSchinazi/ssh-charter/issues/1)
about acronym conflicts ]

# Charter

The main goal of the working group is to maintain the Secure Shell (SSH)
protocol. SSH provides support for secure remote login, secure file transfer,
and secure TCP/IP and X11 forwardings. It can automatically encrypt,
authenticate, and compress transmitted data.

At the time of writing this charter, it has been more than 17 years since the
previous Secure Shell WG has been closed and its documents published. In the
intervening years, implementations and RFCs have diverged. The first goal of
this new working group is to update the RFCs documenting SSH to reflect what is
currently implemented and deployed in practice. In particular, the working
group will document the OpenSSH certificate structure, the SSH agent protocol,
and SFTP, as they are commonly implemented.

A second goal of this working group is to update and maintain the list of
cryptographic algorithms used by SSH. This includes documenting existing
algorithms, deprecating unsafe algorithms, defining new algorithms (such as
post-quantum), and determining the set of recommended and
mandatory-to-implement algorithms. Updating IANA SSH registries and changing
their registration policies is in scope.

While the development of formal verification proofs is out of scope, this
working group can respond to emerging proofs, and to security issues found by
formal verification tools. This can be done for example by defining new
extensions to improve the security of SSH.

This working group will strive for simplicitly and ease of implementation. In
particular, proposals should only be adopted if there is interest in real
implementation and deployment. Protocol documents should not be submitted to
the IESG for publication before they have been implemented.

Defining new certificate types or trust mechanisms is out of scope. New
transports for SSH are out of scope. While defining how SSH uses cryptographic
algorithms is in scope, defining the algorithms themselves is out of scope.
