﻿# Learning-PHP-7-master-2023-update
 Hello, if you are here you must have read the book "Learning PHP 7"
 this repository contains the updates to all the necessary dependencies, like twig, monolog, etc
 this file was updated in 2023 to all the latest versions for all dependencies.
 Your main folder should be named: bookstore
 Here are some of the changes that were notable and changed
 OLD                                          NEW
// deprecated methods
 use Twig_Loader_Filesystem;                  use Twig\Loader\FilesystemLoader;
 use Twig_Environment;                        use Twig\Environment;                  
Logger::DEBUG                                 Level::Debug
