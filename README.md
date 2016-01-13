# EarthQuakeIndiaPy
Python program to get Earthquake Information from python program in India and neighbouring areas


#Usage

    >>> import EarthQuakeIndiaPy as e
    >>> e.getLastKnownQuake()
    {u'Intensity:': u'MODERATE', u'Time:': u'11:17:32.0 HRS(IST)', u'Region:': u'NORTHERN SUMATRA', u'Depth:': u'30 km', u'Date of Occurence: ': u'13/01/2016', u'Magnitude:': u'5.1', u'Epicentre:': u'Lat. 00.6\xb0N Long. 92.3\xb0E'}
    >>>e.getLastMonthData()
    #returns a list of Earthquake dict object
    >>>e.getCurrentMonthData()
    #returns a list of Earthquake dict object
    
    
##EarthQuakeObject Sample

{u'Intensity:': u'MODERATE', u'Time:': u'11:17:32.0 HRS(IST)', u'Region:': u'NORTHERN SUMATRA', u'Depth:': u'30 km', u'Date of Occurence: ': u'13/01/2016', u'Magnitude:': u'5.1', u'Epicentre:': u'Lat. 00.6\xb0N Long. 92.3\xb0E'}
  
Data of EarthQuake is fetched from http://imd.gov.in/
