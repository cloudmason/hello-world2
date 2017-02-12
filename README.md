# hello-world2
Tutorial repository
This is a simple README file used for training purposes only.

Introduction

SCMS is a software configuration management system based on the CVS revision control tool and supports concurrent development on multiple release threads and uses a logical change, or ECO, checkin model. It also provides an enhanced set of administrative commands for managing repositories, and additional inquiry commands for users and administrators.

Contents

This document provides a high-level description SCMS in general and the ECO check-in paradigm. The principal topics are:

The ECO Paradigm
Release Threads and ECO Migration
SCMS Objects
SCMS Command Summary
Glossary
The ECO Paradigm

SCMS is designed to support an ECO check-in paradigm. This model requires that the set of file and directory changes used to implement a single logical change first be associated with an ECO name, and then be checked-in as a unit. Individual files cannot be checked-in without first being associated with an ECO. The basic operations a user must perform under this paradigm are shown below.

