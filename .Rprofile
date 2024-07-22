# only run if in a GitHub codespace
if (nzchar(Sys.getenv("CODESPACES"))) {
  source("renv/activate.R")
  if (requireNamespace("BiocManager", quietly = TRUE)) {
    Sys.setenv("RENV_CONFIG_PAK_ENABLED" = "true")
  }
}
