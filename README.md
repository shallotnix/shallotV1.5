# ShallotV1.5

A simple 20-minute break reminder timer built with GTK4.

## Description

Shallot is a desktop application that implements the **20-20-20 rule**: every 20 minutes, it reminds you to look away from your screen for 20 seconds to reduce eye strain.

## Requirements

- GTK4 (`libgtk-4-dev` or `gtk4-devel`)
- A C compiler (GCC, Clang)

## Build

```sh
gcc shallot.c -o shallot `pkg-config --cflags --libs gtk4` -lm
```

## Usage

```sh
./shallot
```

Click **STRAT TIME** to start a 20-minute countdown. When the timer reaches zero, an alert will remind you to rest your eyes. The app tracks how many breaks you've taken. Use **Pause** / **Resume** to pause and resume the timer, and **Reset** to reset it.
