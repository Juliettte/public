---
layout: post
title: Local time discretisation for linear wave equations
date: 2021-01-05
description: some highlights on the construction and analysis of local time discretisation for linear wave equations
tags: numerics energy
categories: numerical-scheme energy local
related_publications: chabassier:hal-03309010, chabassier:hal-01222072
---
This page describes contributions that provide coupling of different time integration strategies, leading to local time integration. A domain decomposition approach allows to derive
  * a coupling of different fourth order schemes over a boundary,
  * a coupling of explicit and implicit second order scheme,
  * a coupling of explicit schemes with different stability conditions, 
  * the space time convergence proof of the previous strategies, for a small enough time step
