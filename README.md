# buffer_I-O
This is the repository for buffered I/O in GoLang.
The bufio package provides a buffered I/O in GoLang.If we send data to a buffer with a limit l then the buffer will take all those data and will not write until it reaches the length l. After which it writes the data and flushes the buffer. And the operation goes this way.
Buffered IO is useful in many different scenarios. Where many writes happen at the disk it can provide a solution to the problem by creating a custom buffered writer suitable for the needs. The buffered reads help to do the same but with reads.
