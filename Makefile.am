## Process this file with automake to produce Makefile.in

## This is a part of imgs2html
## Copyright (C) 1999-2000, Masao Takaku, Yuka Egusa. All rights reserved.

bin_SCRIPTS =	imgs2html ps2imgs
man_MANS =	imgs2html.1 ps2imgs.1

EXTRA_DIST =	$(man_MANS)

$(man_MANS):	configure.in
	pod2man --center="imgs2html" --release="imgs2html $(VERSION)" \
		imgs2html > imgs2html.1
	pod2man --center="ps2imgs" --release="ps2imgs $(VERSION)" \
		ps2imgs > ps2imgs.1
