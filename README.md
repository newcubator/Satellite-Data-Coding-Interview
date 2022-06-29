# Satellite Data Coding Interview

This coding challenge is a simplified real world problem we were facing during one of our projects.

## General Information

This challenge is about satellite image metadata for fields. Each field is monitored by satellites which take pictures of it multiple times a week in different spectrums resulting in multiple images per shot. These images are differentiated by their `layer_name` (NDVI, NDWI and TRUECOLOR). The satellite also detects if there are clouds above a field and calculates a `cloud_coverage` percentage.

## User Story 1

As a user I want to be able to query satellite image metadata to see what's going on on my fields. For each field I want to determine the best (in terms of cloud coverage) satellite image per layer with a weekly resolution to have a good visualization of my fields.
