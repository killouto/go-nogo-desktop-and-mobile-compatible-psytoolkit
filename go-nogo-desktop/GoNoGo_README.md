# Go/No-Go Task (Persian)

This is a translated and adapted version of a classic **Go/No-Go task** designed for use with [PsyToolkit](https://www.psytoolkit.org/). The task has been localized in **Persian** and optimized for **both desktop and mobile platforms**.

## Purpose

The Go/No-Go task is used to assess **inhibitory control**, a core executive function. Participants are instructed to respond to certain stimuli (Go) and withhold their response to others (No-Go).

## File Contents

- `code.psy`: The PsyToolkit script for the task
- `stimuli/`: Folder containing visual materials

## Data Output

The output data consists of **3 columns**:

| Column | Description                       |
|--------|-----------------------------------|
| 1      | Signal Type (`go` or `nogo`)      |
| 2      | Reaction Time in milliseconds     |
| 3      | Accuracy (`0` = correct, `1` = incorrect) |

- A `go` signal followed by a valid keypress will yield `0` if correct.
- A `nogo` signal followed by no response will yield `0` (correct inhibition).
- Any failure to inhibit on `nogo`, or miss on `go`, will result in `1`.

## Attribution

Original experiment design and script by Gijsbert Stoet, PhD , PsyToolkit developer  
**Translated and adapted into Persian by Sepehr Moraghebi** for mobile and desktop compatibility.

## License

This task is part of the [Persian Cognitive Tasks](https://github.com/killouto/cognitive-tasks-persian-mobile-desktop) repository and licensed under the MIT License. See the [LICENSE](../LICENSE) file for more information.
