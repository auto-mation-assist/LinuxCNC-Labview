# Status
 The Network TCP interface for reading the emcStatus buffer. This polls the status buffer at 30ms intervals. Data that
 it obtains is the sent to the various decode and distribution functions which are a seperate process and not in this VI.
 Adjust the network address to suit your system. This uses Labview Community 2020 and requires the JKI state machines which
 can be added to Labview with the VI package manager, in its VIPM2020 list of avlaibale additions. It will automatically
 connect with LinuxCNC if the port and address are correct and linuxcnc is available on the network.
