# Abstract Factory Furniture Shop

A Python class assignment demonstrating the **Abstract Factory** design pattern through a furniture shop example.

## Overview

The shop creates matching furniture in three styles: **Modern**, **Victorian**, and **Art Deco**. Each style includes a chair, table, and sofa.

## Design

- **Abstract products:** `Chair`, `Table`, and `Sofa` define the product interfaces.
- **Concrete products:** Implement the furniture for each style.
- **Abstract factory:** `FurnitureFactory` defines the interface for creating a family of furniture.
- **Concrete factories:** Create Modern, Victorian, or Art Deco furniture.
- **Client:** Selects a furniture family and uses its factory to create matching products.

## Purpose

This project demonstrates how related objects can be created without tying client code to specific concrete product classes. Switching factories changes the furniture style while keeping the same product interfaces.

## Technology

Python, object-oriented programming, and the Abstract Factory design pattern.
