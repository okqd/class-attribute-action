# class-attribute-action
to learn class and its attribute,action
# -*- coding: utf-8 -*-
class Person(object):
     address = 'beijing'
     def __init__(self,name,gender):
          self.name = name
          self.gender = gender
     def get_name(self):
          return self.name

p1=Person('lily','female')
print p1.get_name(),p1.name,p1.gender
#action is also attribute, p1.get_name() == p1.name, the former is action, the letter is attribute,so we can say action is attribute
