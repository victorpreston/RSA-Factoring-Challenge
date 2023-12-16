#!/usr/bin/env python3
'''Module - Factors natural numbers'''

from  __future__  import  division
import sys
import os


def func_factors(filename):
    '''Read and find Factorials of every line '''
    with open(filename, 'r') as f:
        for line in f:
            num = int(line)
            resul = factors(num)
            print ("{}={}*{}".format(num, int(num / resul), resul))
    f.closed

def factors(x):
    '''Returns the minimun factorial number '''
    for y in range(1, x + 1):
        if x % y == 0 and y is not 1:
            return y

if __name__ == "__main__":
    '''main'''
    if (len(sys.argv) is not 2):
        raise SyntaxError("[BAD-USAGE]: Expected only one argument")
    func_factors(sys.argv[1])
