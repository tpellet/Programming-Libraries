#' set working directory to active document path
#'
#' set working directory to active document path
#' @param none
#' @return none
#' @examples 
#' set_wd()
#' @export
set_wd <- function() {
library(rstudioapi) # make sure you have it installed
current_path <- getActiveDocumentContext()$path 
print(current_path)
setwd(dirname(current_path ))
print( getwd() )
}

#' printhello
#'
#' Print the Hello world command
#' @param none
#' @return none
#' @examples 
#' printhello()
#' @export
printhello <- function() {
  print("Hello World")
}