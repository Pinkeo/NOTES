#### Referents
video : [[vid.Full Bridge Rectifier Explained]]
lao Script : [[Lao.Script.Full Bridge Rectifier Explained]]

___

Learn about the full bridge rectifier – how to convert AC alternating current into DC direct current. Using capacitors to filter the rippled DC wave into smooth DC with experiments.

Remember, electricity is dangerous and can be fatal. You should be qualified and competent to carry out any electrical work.

**Scroll to the bottom to watch the YouTube tutorial.**

The most common method used is the full wave bridge rectifier. This uses four diodes nodes. The AC supplier is connected between diodes one and two, with the neutral between three and four. The DC positive output is connected between diodes two and three, and the negative between diodes one and four. In the positive half of the sine wave, the current flows through diode two, through the load, through diode four, and then back to the transformer.

In the negative half, the current flows through diode three, through the load, through diode one, and then back to the transformer. So the transformer is supplying an AC sine wave, but the load is experiencing a rippled DC waveform because the current flows in just one direction. In this example circuit, we can see that rectified waveform on the oscilloscope, but this is not a flat DC output, so we need to improve this by adding some filtering.

Using a rectifier will result in a ripple in the waveform. To smooth this out, we need to add some filters. The basic method is to simply add an electrolytic capacitor in parallel to the load. The capacitor charges during the increase in voltage and stores the electrons. It then releases these during the decrease.

This therefore reduces the ripple. The oscilloscope will show the peaks of each pulse, but now the voltage doesn’t decrease to zero. It slowly declines until the pulse charges the capacitor again. We can further reduce this by using a larger capacitor or by using multiple capacitors. In this simple example, you can see the LED turns off as soon as the power is interrupted.

But if I placed a capacitor in parallel with the Led, it remains on because now the capacitor is discharging and powering the LED during the interruptions. In this circuit, I have a lamp connected as the load. The oscilloscope shows the rippled waveform. When I add a small ten microfarad capacitor, we see that it makes very little difference to the waveform. When I use a 100 microfarad capacitor, we see the dip is no longer down to 0 volt.

At 1000 microfarads, the ripple is very small. At 2200 microfarads, it’s nearly completely smooth. This would be fine to use for many electronic circuits, we could use multiple capacitors also. Here we have a 470 microfarad capacitor, which has made some difference. But if I use two capacitors in parallel, we see the waveform is much more improved.

When using a capacitor, we need to place a bleeder resistor across the output. This is a high value resistor, which will drain the capacitor when the circuit is off to keep us safe. Notice with this circuit that when I switch it on, the capacitor charges quickly to over 15 volts. But when I switch it off, the DC output is still at 15 volts because there is no load, so the energy is still stored in the capacitor.

This could be very dangerous if the voltage is high. In this example, I place a 4.7K Ohm resistor across the output. We see the capacitor charges up to 15 volts and when I switch it off, the capacitor quickly discharges. The electrons are flowing through the resistor which discharges the capacitor. We can also see that without a capacitor, the output voltage is lower than the input voltage because of the voltage drop of the diodes.

Here we have a simple full wave bridge rectifier on the input. We see there is 12 volts AC on the output. We have ten 5 volts of DC. The voltage on the output is lower because of the diodes. Each diode has a voltage drop of around zero 7 volts.

If we look at this circuit with a diode and an Led, we can measure across the diode to see a voltage drop of around zero 7 volts. The current in our Fullbridge rectifier must pass through two diodes on the positive half and two diodes on the negative half. So the voltage drop combines and is around one four to one 5 volts. So that is why the output will be reduced. However, if we were to connect a capacitor across the output, we will see that the output voltage is now higher than the input voltage.

How is that possible? That’s because the AC input is measuring the RMS voltage or the root means squared. This is not the peak voltage. The peak voltage is 141 times higher than the RMS voltage. The capacitors are charged up to the peak voltage and then release.

There will be a small voltage drop because of the diodes, so the output is less than the peak input, but it will still be higher than the RMS input. For example, if we had 12 volts RMS on the input, the peak voltage would be 12 volts multiplied by 1.41, which is 16.9 volts. There will be a 0.7 volt drop here and here. So 16. 9 volts subtract 1.4 is 15.5 volts. The capacitors are charged up to this voltage. This is only the approximate answer, though. The amount of ripple and the actual voltage drop of the diodes will cause it to be slightly different in reality, but we can see that the output is higher than the input. Another common filter is placing two capacitors in parallel with a series inductor between these.

This is used for circuits with larger loads. The first capacitor smooths the ripple. The inductor opposes the changing current and tries to keep it constant, and the second capacitor, which is much smaller, will then smooth out the final remaining ripple. Additionally, we can also connect a voltage regulator to the output. This is very common and allows some variation to the input, but it will provide a constant output voltage.

This again has capacitors on either side of the regulator to ensure a smooth DC output. Here we can see a real version which is connected to a twelve volt AC supply and we see it has an output of around five V DC.
