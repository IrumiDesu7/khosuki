# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a single-page HTML website for "Khosuki Laundry Sepatu", a shoe cleaning service business. The project is a standalone static website with no build process or dependencies.

## Architecture

- **Single HTML file**: `index.html` contains all HTML, CSS, and JavaScript
- **Embedded styles**: CSS is written in a `<style>` tag within the HTML head
- **Inline JavaScript**: Simple intersection observer for fade-in animations
- **No external dependencies**: Uses only Google Fonts for typography
- **Responsive design**: Uses CSS clamp() and media queries for mobile-first approach

## Development Commands

Since this is a static HTML file with no build process:
- **Preview**: Open `index.html` directly in a browser or use a local server
- **No package.json**: This project has no npm dependencies or scripts
- **No build step**: Changes to `index.html` are immediate

## Code Structure

- **CSS Variables**: Color scheme defined in `:root` selector
- **Component-based CSS**: Classes like `.service-category`, `.hours-card` for reusable styles
- **Animation system**: Intersection Observer API for scroll-triggered animations
- **Mobile-first**: Base styles for mobile with desktop enhancements in media queries

## Design System

- **Colors**: Primary blue (#235789), powder white (#fdfffc), red (#ed1c24), yellow (#f1d302)
- **Typography**: Bungee font for headings, Arial for body text
- **Visual style**: Card-based layout with borders and box shadows for depth

## Key Features

- **Location integration**: Google Maps link for business location
- **Service pricing**: Categorized pricing table with time estimates
- **Operating hours**: Highlighted business hours section
- **Animations**: Fade-in effects on scroll for better user experience