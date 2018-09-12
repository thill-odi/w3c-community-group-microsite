---
description: 'Initial draft of Booking API 1.0, moving to formal publication'
---

# 2018-09-12 - Booking API 1.0

##  Summary

We've just published an initial editors draft of the Open Booking API 1.0. The updated document can be found here:

[https://www.openactive.io/open-booking-api/EditorsDraft/index.html](https://www.openactive.io/open-booking-api/EditorsDraft/index.html)

Changes include:

* Orders now contain arrays of orderedItems and acceptedOffers
* A richer set of error conditions
* Revised modelling on Order, Payment, Error and around where properties

  such as privacyPolicy, termsAndConditions and potentialAction sit

* Improved modelling and documentation relating to cancellation of events
* Introduction of webhook subscription for _brokers_ to be notified of

  events cancelled by _booking systems_

* Moved to use validFrom/validThrough for Offer as it expresses the

  intent more clearly than availabilityStarts/availabilityEnds

* Improved modelling of free offers which brings it into line with

  Modelling Specification 2.0

* Finalised new Booking models for Error and Payment

We are publishing this draft so that we can collect comments and feedback from the community as early as possible.

Please review the latest document and file your feedback on github:

[https://github.com/openactive/open-booking-api/issues](https://github.com/openactive/open-booking-api/issues)

We'd like to get this published as a formal community group deliverable in the next 2-3 weeks.

##  Slides

[https://docs.google.com/presentation/d/1ijrA2aCZOtNTGNIT5o4ZrPmgW0KOe\_Sl9\_JKzg8rNOk/edit](https://docs.google.com/presentation/d/1ijrA2aCZOtNTGNIT5o4ZrPmgW0KOe_Sl9_JKzg8rNOk/edit?usp=sharing)

##  Video

{% embed data="{\"url\":\"https://www.youtube.com/watch?v=8wZ5LZZTO\_M\",\"type\":\"video\",\"title\":\"OpenActive W3C Community Group Meeting /2018-09-12\",\"icon\":{\"type\":\"icon\",\"url\":\"https://www.youtube.com/yts/img/favicon\_144-vfliLAfaB.png\",\"width\":144,\"height\":144,\"aspectRatio\":1},\"thumbnail\":{\"type\":\"thumbnail\",\"url\":\"https://i.ytimg.com/vi/8wZ5LZZTO\_M/maxresdefault.jpg\",\"width\":1280,\"height\":720,\"aspectRatio\":0.5625},\"embed\":{\"type\":\"player\",\"url\":\"https://www.youtube.com/embed/8wZ5LZZTO\_M?rel=0&showinfo=0\",\"html\":\"<div style=\\\"left: 0; width: 100%; height: 0; position: relative; padding-bottom: 56.2493%;\\\"><iframe src=\\\"https://www.youtube.com/embed/8wZ5LZZTO\_M?rel=0&amp;showinfo=0\\\" style=\\\"border: 0; top: 0; left: 0; width: 100%; height: 100%; position: absolute;\\\" allowfullscreen scrolling=\\\"no\\\"></iframe></div>\",\"aspectRatio\":1.7778}}" %}

