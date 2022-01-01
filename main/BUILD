
cc_binary(
    name = "gtk-ex",
    srcs = ["gtk-ex.cpp"],
    copts = ["-Iexternal/gtest/include",
            "-Iexternal/gtk",
            "-Iexternal/glib/includes",
            "-Iexternal/gdk"],

    deps = ["//lib/gtk:gtk",
	    "//lib/glib:glib",
	    "//lib/gdk-pixbuf:gdk-pixbuf",
	    "//lib/cairo:cairo",
	    "//lib/hb:hb",
	    "//lib/atk:atk",
	    "//lib/pango:pango",
            "//lib/gdk:gdk",]
)
