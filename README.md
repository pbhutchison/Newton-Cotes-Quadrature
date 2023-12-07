---
Name: Paul Hutchison
Topic: 28
Title: Newton-Cotes Quadrature
---

# Newton-Cotes Quadrature

## Table of Contents

- [Overview](#overview)
- [Background](#background)
- [References](#references)

## Overview

The Newton-Cotes Quadrature or Newton-Cotes Formulae are a type of a broader class of algorithms known as numerical quadrature, which aim to approximate the results of definite integrals. These algorithms are essential for functions $f(x)$ that do not have an antiderivative $F(x)$, which would prevent us from applying the Fundamental Theorem of Calculus $I(f) = \int_a^b f(x)dx = F(b) - F(a)$ to compute definite integrals [1]. For example, the Gaussian Function, $e^{-x^2}$, is known not to have an antiderivative; however, computing its definite integral is essential in probability and statistics [2].

## Background

Numerical quadrature algorithms function by what are known as quadrature rules. These rules aim to replace the integral with the summation of the product between the integrand evaluated at each quadrature point $x_i$ and a corresponding quadrature weight, $w_i$ [3].
$$\int_a^b f(x) dx = \sum_{i = 1}^n f(x_i)w_i$$

## Implementations of Newton-Cotes Quadrature

## Shortcomings of Newton-Cotes and Alternate Methods

## Handling Edge Cases

## Extending to Composite Quadrature

## References
