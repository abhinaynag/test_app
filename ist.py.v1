import re, os, sys, string , traceback
import splunk.Intersplunk as si

try:
	results ,dummyresults , settings   = si.getOrganizedResults()
	#writeout(results)
	si.outputResults(results)
	fo = open("op.txt" , 'w')
       	fo.write(results)
       	fo.close()
except:
		error=traceback.print_exc()
		si.generateErrorResults(error)

'''def writeout(results):
	fo = open("op.txt" , 'w')
	fo.write(results)
	fo.close()'''
		
