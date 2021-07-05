### Board c8 and c6

one defective ADC found

### Board c7

Several DACs are broken and only emit a signal of 0. Because the calibration algorithms use DACs to measure signals, tiles with non-functional DACs also have mis-calibrated blocks. If one of the calibration DACs is not functional, all block modes which involve high dynamic range signals (h). Because the faulty calibration DACs emit 0, the medium mode for all the blocks should still be usable; this is why we get some good results.

- I'll test all DACs on this board after defending

#### Defective Dac List
DAC (0,0,0,0): (const,m),(const,h),(dyn,m),(dyn,h)
DAC (0,0,1,0): (const,m), (const,h) [(dyn,m) and (dyn,h) unknown]
DAC (0,0,2,0): (const,m), (const,h), (dyn,m), (dyn,h)
DAC (0,1,0,0): (const,m),(const,h), (dyn,m), (dyn,h)
DAC (0,1,2,0): (const,m), (const,h), (dyn,m), (dyn,h)
DAC (0,2,0,0): (const,m), (const,h), (dyn,m), (dyn,h)
DAC (0,2,2,0): (const,m), (const,h), (dyn,m), (dyn,h)
DAC (0,3,0,0): (const,m), (const,h)
DAC (0,3,2,0): (const,m), (const,h)
DAC (1,0,0,0): (const,m), (const,h) (dyn,m), (dyn,h)
DAC (1,0,2,0): (const,m), (const,h) (dyn,m), (dyn,h)

#### Working Dac List
DAC (0,3,0,0): (dyn,m), (dyn,h)
DAC (0,3,1,0): (const,m), (const,h)
DAC (0,3,2,0): (dyn,m), (dyn,h)

### Board c9

Cannot connect to arduino.


