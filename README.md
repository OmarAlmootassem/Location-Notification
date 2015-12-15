# Location Notification
Location Notification is an android application that automates your phone's notification settings. It periodically checks your location and adjusts your phone's notification setting to the requested setting (Normal, Vibrate, Silent).

##Main Activity
This is what opens when you first launch the app. It gives you a switch to enable/disable the app and a floating action button to add a preset. Given that this app is built with android Marshmallow's permission system in mind, it will ask you to accept the permissions it needs to run smoothly.

![Main Screen](https://lh3.googleusercontent.com/6UaMl6RLiOY2jhCU5FthoGN-Zm0LgqZgQLSxAYsV5IczR-JnN_0awaBjkg9kHQY9-mEZ0yN02tfNShsD5SyP1XCXklll8MEAAEbeFI3BakG4gZ3HVFASB0CcKjjAR2DO1m4mF0p1o8IvTNechCR5i76NBCYkgixIKnGmJTzXqfZc6l26gb-LLFuuB8d4yWXbz9N_6-ofccE_K_6TjsnTBK-siPDWTKz2jnHgfiKqF6gbSBAJzozIE63orKpsZiSEVVGj8f4iTQMLYpLLUXpRb8c5OPTX0rfqrcqBabRg8d3_TaklIao7a97Ib2UL9ElsrOAE79TvPSbE_nGkyG81W2lMlai5I6sLL2pJZMCK0FfY3MroW8LoNMzsQClKzYHHeXsDGlgVi28KtIxlCC0SvSITnr7eg0pDJFxeCb1wrzfqo0c7fSSO26cFHXEOoB8fq791uYrd_dwWWwu4LNGiqhmKJ2uLfzZxE8OM73EnnA07XLZEv1R_P-Uu0aHfwUdnhqoIyP62376alwYAsMWUYEHBUbfVeHJ-on1iNu7gwXhHz_p9qvtkfnE_C5k8EzdkXbaD=w551-h979-no)

##Add Preset Activity
This activity is launched when the floating action button in the previous activity is pressed. In this activity, you add a preset by choosing the location, notification setting, and the place nickname. It uses Google Maps API to display the map and it uses Google Places API for the autocomplete place search box.

![Add Preset Screen](https://lh3.googleusercontent.com/_UYCE-k3Dstj6OEsta0eTW20oeDUC62-8tWO7_xNlpUGgQAlZoJBS4rI23hZsyRH0rOivsBqKGnaFvmbLhmebAaCM3EcmIU8E_1iYGcqvTYJTqtxht4-y4_lwMVZSqJUKv98MoT99IzD6KM-xaVeyZhO2kv73wXMOb4gD8VkwvVcGV04OnJO86O4JAopnRrL1T9f9VCS9lU0F4XxElnnC4rtrVqBrftDt4hqBv7qKIdI7LCClByyE3Wps20PQqutK_9PJafSvnyb_SOkQEpVxfNhk7sic-853WjtYBmVHV16FJmZt9ZRxdvGHZ0XwJzTZNzXOkEU-VI_2xqP6b0j2jSu-iqyx036FbodbX0_ly56BU1KAGapNNLFVRt1T5JdwgAt4fld9CCvJQcZrOflGbezATjJOSJquQjxS8WnMwLjKXpnlVu2Qv80q4Inu_FsTLrjzZCxiyQmj5mbnR3b-U6CbrqAZCBks2iO4E7bSQ9WbHIzEsVnSuwc_PmqftuyZsh7Z2r_ykdHgFYlj5FJmdHR8QTdH65dqMHXaltDtcGnRqh8cBcZ8uKkE8LEnAj85kqi=w551-h979-no)
