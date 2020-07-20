# enzo clk

## Why

The goal is Focus.

The goal is not the fruits of Focus.

Pomodoro Timeboxing (Timeslicing) is a great tool for maintaining focus. `enzo clk` is a customizable Pomodoro Timebox.

## Requirements

- default 15 min boxes (13+2)
- timer beeps
    - 2 beeps at every 5th minute in each hour
    - 10 beeps at startof a time slice
    - 10 beeps at end of a time slice
    - vocal/beep warning 10s before end of timeslice
    - 1 beep at every 10s during a break
    
- works like Repeat Alarm Android app
    - time boxes are driven using system clock, not using a timer

## Design

## UX

A user will run command `enzo focus-clk` to start the timer with defaults.

## Design

### Components

- a set of predefined events signifying every event in the scope of `enzo focus-clk`
- a clk generating events/signals every second
- a component which checks the time event and decide whether there is a significance for that event (time). If the time 
  if the time is significant emit respective event.
- a set of methods which can execute proper actions for particular event
- a component which invokes the right method/handler for events received

## Implementation



 
