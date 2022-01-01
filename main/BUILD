load(":ex.bzl", "procme")


cc_binary(
	name = "gtk-ex",
	srcs = ["gtk-ex.cpp"],

	deps = ["//lib/gtk:gtk",
	 "//lib/glib:glib",
	 "//lib/gdk-pixbuf:gdk-pixbuf",
	 "//lib/cairo:cairo",
	 "//lib/hb:hb",
	 "//lib/atk:atk",
	 "//lib/pango:pango",
	 "//lib/gdk:gdk",],

	linkopts = procme(),
)





