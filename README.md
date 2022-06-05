liburing-0.11.x-srpm
=====================

SRPM building tools for liburing-0.2.x for runing Samba 4 on RHEL 8.

The "make" command will do these steps.

	make build	# Build the package on the local OS
	make all	# Use "mock" to build the packages with the local
			# samba4repo-6-x96_64 configuration, which needs.
	make install	# Actually install the RPM's in the designated repo

		Nico Kadel-Garcia <nkadel@gmail.com>
