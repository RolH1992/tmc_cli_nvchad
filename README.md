TMC CLI Rust in NVCHAD

This is a showcase integration of the tmc-cli-rust plugin within the NVCHAD Neovim configuration. TMC (TestMyCode) is a system used in programming courses for automated testing and exercise submission.
Features in NVCHAD:

    TMC command integration - Access TMC functionality directly from Neovim

    Exercise management - Download, test, and submit programming exercises

    Rust-based performance - Faster execution compared to the original Java implementation

    Seamless workflow - Integrated with NVCHAD's existing tools and keybindings

Basic Commands Available:
text

:TmcLogin           # Authenticate with TMC server
:TmcCourses         # List available courses
:TmcDownload        # Download exercises
:TmcTest            # Run tests on current exercise
:TmcSubmit          # Submit exercise for grading

Note:

    This is not my original code - it's the official tmc-cli-rust by Rage integrated into NVCHAD

    The plugin provides a modern, efficient CLI for TestMyCode operations

    Perfect for students using TMC-based programming courses (like MOOC.fi, University of Helsinki courses)
