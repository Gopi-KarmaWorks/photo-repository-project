# INFO 4730 REpository Project

## Overview
This is a repository that I've created for the Repository Project in my INFO 4730 class. It is a small digital photo repository. Currently, it will be storing lower quality copies of the original photos, with the larger photos being stored locally. 

## Users
The primary user will be myself, and the repo will continue to be managed by myself. 

## Purpose
The Purpose of this repository is to simply store and organize a small smaple of images, in a consistent and easy to retreive manner. While yes, I've created this specifically due to the project, This repo will still be serving as a proof of concept for a much larger repository in the future. 

## Repo Structure

- collection/events/ = For event and other client related photography work. 
- collection/travel/ = For photos taken while I've been traveling. 
- metadata/ stores a CSV file containing item-level metadata. 

## Metadata Fields

- item_id
- title
- creator
- date_created
- format
- tags

## Metadata Rules

- Images in the same batch may share a majority of the same tags, but atleast one of them must be different from one another.
- No less than 5 Tags, and no more than 15 tags per image. 
- If an image's creation date is known, Use the date of ingestion, and use the full datetime format 00/00/0000 rather than 00/00/00. 

## Naming Rules

-Photos taken in the same batch must share atleast mostly the same name, with the difference being distinguied by a number
 IE: Two photos taken at a fashion show named "Fashion_Portrait-1" and "Fasion_Portrait-2". 
- Words must be distinguished with an underscore (" _ "), while numbers will be attached with a dash (" - "). 


## Items Currently Stored
There are 5 sample photos currently ingested into the system. 

## Access
The github is currently a public repository, meaning anyone will be able to access the repository and it's contents. The repository will be archived at the conclusion of this semester. 

