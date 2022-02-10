#!/usr/bin/python3
# -*- coding: utf-8 -*-

class Human:

    def __init__(self):
        self.name = "Halocytus"
        self.role = "Cybersecurity Enthusiast"
        self.language_spoken = ["es", "en", "fr"]

    def introduce_myself(self):
        print("Currently script kiddie and will always be")
        print("Studying Cybersec and proud member of kucss")
    
    def github(self):
        print("I'm going to be uploading interesting tools that can be useful for me/you in the future") 

################main######################
me = human()
me.introduce_myself()
me.gtihub()
