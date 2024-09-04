# SPARS
SPARS - Scalable Paging Automatic Relay System is a notification system that takes national paging data and relays messages for the Fire and Ambulance Services in New Zealand. It's filters are customisable for each user allowing for efficency and awareness for its users

To get set up with SPARS (Currently in the Testing Phase) follow the instructions below:

## 1. 
Install PUSHOVER, a notification application avalible on almost all platforms,

## 2.
Launch the client and it will walk you through creating a Pushover account and registering your device with PUSHOVERS servers.

## 3.
You'll get a new User Key e-mailed to you (which you can always find on your dashboard or through the Settings menu of the Pushover client app on your device). Your User Key is a randomly generated identifier which allows other apps like SPARS to send Pushover notifications to your devices.

## SPARS SETUP FORM: 
https://forms.gle/gcvTe2bLNadKRFip6

## 6.
Provide your PUSHOVER User Key to SPARS form

## 7.
Choose your custom filter for your notifications and provide it to SPARS form
   - FENZ Appliances / Callsigns 
   - Ambulance Callsigns
   - Suburbs to Monitor for Ambulance calls and the priority of notifications for all call signs
   - Specific Priority Keywords that will trigger a Emergency Notification (Critical Alert)
   - Blacklist - Somtimes callsigns from other areas will notify you due to similarity in suburb names, this can be updated over time to fix any unwanted alerts
  
   For Fire you can select the priority of notification for each callsign (SILENT [-1], NORMAL [0], HIGH [1])
   For Ambulance you can select the priority of all notifications

   An example of a filter seen here:

  Fire List: (Callsign : Priority)
      'KARI5271': -1,
      'KARI5276': -1,
      'PUHO7471': 1,
      'PUHO7425': 0,
      
  Ambo List: (Suburbs & Callsigns)
      "SILVERDALE ",
      "RED BEACH ",
      "MILLWATER ",
      "WAINUI ",
      "MANLY ",
      "MANLY1",
      "MIKE15",
      "ECHO12",
      "ECHO24",
      
  Blacklist: (Callsigns & Keywords)
      'PALM1',
      'PALM2',
      'WHNG1',
      
  Priority Keywords (Sends an Emergency Alert [Priority = 2]:
        " LINE RESCUE ", 
        " TX ", 
        
  Ambulance Priority: 0
   

For more information on PUSHOVER (which is a separate service to SPARS) please see their website: https://support.pushover.net/i7-what-is-pushover-and-how-do-i-use-it
