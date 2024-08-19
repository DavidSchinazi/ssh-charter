# Metadata

* Working group name: Secure Shell Maintenance
* Working group acronym: SSHM
* Mailing list: ssh@ietf.org

# Charter

The main goal of the working group is to maintain the Secure Shell (SSH)
protocol. SSH provides support for secure remote login, file transfer, and
forwarding UNIX-domain sockets, TCP/IP and X11. It can automatically encrypt,
authenticate, and compress transmitted data.

The SSHM working group facilitates discussion of clarifications, improvements,
and extensions to SSH protocol. The working group also serves as a focus point
for other IETF Working Groups who use SSH in their own protocols.

The initial goals of this working group are:   

* to update the RFCs documenting SSH to reflect what is implemented and
  deployed in practice. In particular, the working group will document the
  OpenSSH certificate structure, the SSH agent protocol, and SFTP, as they are
  commonly implemented.

* to update and maintain the list of cryptographic algorithms used by SSH.
  This includes documenting currently deployed algorithms, deprecating
  unsafe algorithms, selecting new algorithms, and determining the set of
  recommended and mandatory-to-implement algorithms. Updating IANA SSH
  registries and changing their registration policies is in scope.

* while the development of formal verification proofs is out of scope, this
  working group can respond to emerging proofs, and to security issues found by
  formal verification tools. This can be done for example by defining new
  extensions to improve the security of SSH.

This working group will strive for strong security, simplicity, and ease of
implementation. In particular, proposals should only be adopted if there is
evidence of significant existing deplpyment or broad interest in new
implementation and deployment. Protocol documents should not be submitted to
the IESG for publication before they have at least two demonstrably
interoperable implementations.

Out of scope initially includes:  
  * defining new certificate types or trust mechanisms;
  * new transports for SSH;
  * while defining how SSH uses cryptographic algorithms is in scope, designing
    the algorithms themselves is out of scope.
