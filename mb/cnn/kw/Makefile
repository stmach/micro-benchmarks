# Copyright (c) 2017 OPRECOMP Project
# Fabian Schuiki <fschuiki@iis.ee.ethz.ch>

all:
	$(MAKE) -C pulp clean all disdump disopt="-d -l"
	$(MAKE) -C host

run: all
	host/build/conv pulp/build/system.oprecompkw/conv/conv
