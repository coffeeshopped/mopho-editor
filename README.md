# Mopho Editor

A patch editor for the Dave Smith Instruments Mopho synthesizer, written in Max.

## Installation

To use this software, you'll need a copy of Max from Cycling '74, which can be downloaded from their website: <a href="https://cycling74.com/downloads/">https://cycling74.com/downloads/</a>.

Download all of the included files, and make sure you keep them in the same directory together.

## Usage

Once you have Max installed, open the file mopho-editor.maxpat to run the editor. To configure your MIDI settings within the editor you need to double-click the "midiin" and "midiout" boxes on the right side of the editor. When double-clicked, each box will show a list of available MIDI ports for you to select from, to communicate with your Mopho synthesizer.

To get the current patch from your synthesizer loaded into the editor, click the "get current edit patch" button on the right side of the screen.

Once configured, all changes you make within the editor will be instantly sent to your Mopho.

The file mopho-librarian.maxpat is a separate tool, which can be used to list the names of all of the patches currently stored on your Mopho. I find this useful for my personal bookkeeping.

## Background

I first wrote this editor for myself to use with my Mopho desktop synth. It works pretty well, but has some small bugs still. If you have an iPhone or iPad, I've created an app called Mopho Touch which is a lot more polished and full-featured, available here: <a href="https://coffeeshopped.com/mopho-touch">https://coffeeshopped.com/mopho-touch</a>
