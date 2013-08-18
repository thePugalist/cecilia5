MIDI - OSC control
===================

MIDI
-------

It is possible to use a MIDI controller to have a finer control on sliders and knobs related to the different parameters in Cecilia5.  To use a MIDI controller, please connect it to your system before and be sure that it has been detected by your computer.

Check the "Automatic Midi Bindings" in the Preferences (menu "Cecilia5") to have your controller be automatically detected by Cecilia5. Some parameters will be assigned by default to a controller. For example, the controller 7 will often be assigned to the gain control (in decibels) of the output sound file (see the corresponding slider in the "Output" section).

However, most parameters will have to be assigned to a controller with the MIDI learn function. The "rangeslider" parameters will have to be assigned to two different controllers, for the minimum and maximum values.

To link a parameter to a MIDI controller with the MIDI learn function, right-click on the parameter label you want to control and move the knob or slider of the MIDI controller to enable the connection.  Then, the controller number should be written in the slider of Cecilia5's graphical interface.  To disable the connection, press "shift" and right-click on the parameter.

OSC
-------

It is also possible to control the parameters with the Open Sound Control (OSC) protocol.  To enable an OSC connection, double-click on the parameter label you want to control, enter the destination port address in the window that will appear and click on "Apply":

.. image:: /images/OpenSoundControl.png

Please be aware that activating an OSC connection will automatically disable the previons MIDI connection related to the chosen parameter.