# Guido's 68000 Computer


## Motivations

- I want to learn how actual computers work, not just the CPU, but how it boots up and communicates over a bus
- I want a simple computer that I can use that is completely disconnected from the internet with no distractions and no security concerns

## Prinicples

- Instant boot with large sections of OS/apps in memory mapped ROM
- Inspectible bus with LEDs

## Design Details

- We will use FC0, FC1, and FC2 as 3 extra address pins so we can address 64 MB of RAM (if this really works)

### Clock

- The SK68K uses a high-speed flip flop to divide the crytal's clock
  signal by 2. Apparently this is done to square off the signal better
  and make the duty cycle more even.
  

