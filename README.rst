pyecm2cue
=========

C++ Python Extension To Decode ECM File And Generate Cue File. Code tested in OSX 0.11.6.

Building and Installing
=======================
::

	./setup.py build install

Installing Through PyPi
=======================
::

	pip install pyecm2cue

Python Sample Usage
===================
::

	import pyecm2cue
	pyecm2cue.process("Tekken 3 (E) (Track 1) [SCES-01237].bin.ecm")