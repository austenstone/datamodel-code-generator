--- server/README.md
+++ server/README.md (expected)
@@ -247,5 +247,3 @@
 A server package renamed or moved within the parent package, or spelled from another import root, takes the package over once the package the docstring names is gone, and generation rewrites the docstring to name it; to hand it over while the other package stays, name the new package in the docstring yourself.
 Each generation prints the `uv add` command that adds the runtime dependencies of the package to your project;
 run it again when a new version of datamodel-code-generator changes them.
-
-Changed documentation.
