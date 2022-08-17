# Hailstorm-damaged-analysis

## Summary

Damage assessment caused by hailstorm event in agricultural land, Assiniboia, Saskatchewan, Canada can be observed by satellite EO-based data, particularly Sentinel-2A because of three main reasons: the area is accommodated by one scene of image, the condition before and after hail event is captured without long gap (a day before and 2 days after) therefore the difference is mainly caused by the natural disaster, and the availability of spectral bands that sensitive with the health condition of vegetation. SAVI index is utilized to identify agricultural land that affected by the storm. Change assessment is performed with input from SAVI index before and after the hail event. Then from the difference value, the damaged area can be identified and calculated.

There are two methods that proposed here in order to classifying the damaged and non damaged area, first method relies on visual interpretation for determining the threshold value and the second method is Otsu thresholding which carries the capability of automatically determining the threshold value. However, the manual threshold method shows better deliniaton rather than Otsue threshold method. This is due to the method mostly suitable for data with bimodal histogram. By taking into account the mentioned limitations, this proposed workflow is still leave room for improvement. However, this technical workflow was effectively addressed the challenge and worth implementing. Additionally, with fully performed in python environment which allows to be reproduced and applied for other case studies with some additional improvement in due to create an agile monitoring crop system.
