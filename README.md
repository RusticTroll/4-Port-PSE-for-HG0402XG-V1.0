# 4-Port PSE board for HG0402XG V1.0

I recently purchased [this](https://www.amazon.com/TEROW-2-5G-POE-Multi-Speed-Compatible/dp/B0CGDCBBV3) 2.5G-BaseT/SFP+ "PoE" Switch and was appalled to find out that it does not actually perform PoE classification.
It instead, waits for the resistance that a PD puts on the line, then immediately sends power.
While this may "work" to some extent, it also experiences massive transient current spikes when powering up, which could harm the PD.
It is for this reason that I set out to create a replacement board which is at least better than what was provided.

This is largely just for myself, so there may be errors on the details of specific components. This is definitely not a "production-ready" solution, and I have yet to receive the first copies of the board for testing. **Use at your own risk!**
