
cc_binary(
    name = "gtk-ex",
    srcs = ["gtk-ex.cpp"],
    copts = ["-Iexternal/gtest/include",
            "-Iexternal/gtk",
            "-Iexternal/glib/includes",
            "-Iexternal/gdk"],

    deps = ["//lib:SIM800L",
	    "//gtk:gtk",
	    "//glib:glib",
	    "//gdk-pixbuf:gdk-pixbuf",
	    "//cairo:cairo",
	    "//hb:hb",
	    "//atk:atk",
	    "//pango:pango",
            "//gdk:gdk",]
)
