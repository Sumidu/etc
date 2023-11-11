if (interactive()) {
  suppressMessages(require(usethis))
}
options(blogdown.hugo.version = "0.60.1")

if (interactive()) {
  suppressMessages(require(devtools))
}

options(
  usethis.full_name = "André Calero Valdez",
  usethis.description = list(
    "Authors@R" = utils::person(
      "André", "Calero Valdez",
      email = "andrecalerovaldez@gmail.com",
      role = c("aut", "cre"),
      comment = c(ORCID = "0000-0002-6214-1461")
    )
  ),
  usethis.destdir = "~/r_workspace/_packages/",
  usethis.overwrite = TRUE
)

# warn on partial matches
options(warnPartialMatchAttr = TRUE,
        warnPartialMatchDollar = TRUE,
        warnPartialMatchArgs = TRUE)

# enable autocompletions for package names in
# `require()`, `library()`
utils::rc.settings(ipck = TRUE)

# warnings are errors
options(warn = 2)

# fancy quotes are annoying and lead to
# 'copy + paste' bugs / frustrations
options(useFancyQuotes = FALSE)

if (length(.libPaths()) > 1) {
  msg <- "Using libraries at paths:\n"
} else {
  msg <- "Using library at path:\n"
}
libs <- paste("-", .libPaths(), collapse = "\n")
message(msg, libs, sep = "")
