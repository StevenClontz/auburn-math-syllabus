# auburn-math-syllabus

This is a LaTeX template for the Auburn University math department syllabus template. The goal is to provide TeX-savvy instuctors a way to make a few small changes and easily generate a PDF syllabus fitting departmental policy.

[Click here to download ZIP of files.](https://github.com/StevenClontz/auburn-math-syllabus/archive/master.zip)

[Here's what the finished product looks like.](https://github.com/StevenClontz/auburn-math-syllabus/blob/master/syllabus.pdf?raw=true)

## How to Use

Download the ZIP of files, and open up `syllabus.tex` in your favorite TeX editor. Change all the variables to fit your course, and then compile to PDF.

#### Comfortable with Git?

I've set `.gitignore` to ignore a semesters folder, so here's my workflow:

* Clone the repo as your `master` branch
* `git checkout semester-specific-branch-name` to make a new branch for the semester
* Update `syllabus.tex` to fit your course. 
* If you have any additional documents you want to track on the branch, put them in a folder like `semesters/2013-2`
    * To track that subfolder, make sure to delete `semesters` from `.gitignore`. 
    * You can `\input{../../syllabus_dochead.tex}` to have a shared header file.

## How to Contribute

If you are comfortable with GitHub you are free to submit a Pull Request, or I'd probably be happy to give you edit privileges to the repo directly.

Alternately, just shoot me an email at <steven.clontz@gmail.com> with suggested changes and I'll look into it.

---

### Who are you?...

I'm Steven Clontz. I'm a PhD candidate in mathematics at Auburn Unviersity. I also fancy myself a competent coder, instructor, puzzler, musician, entrenprenuer, etc. etc. Here's my blog if you care: <http://www.stevenclontz.com>

### Who owns this? Who can use it?

This is a derivative work of a Word document written by Dr. T. Y. Tam, department head of Mathematics at Auburn University, adapted for use only by Auburn math instructors. I release any original work into the public domain.

Others who might want to adapt this for their own syllabi may do so, but must rewrite all suggested text and remove any association from the Auburn mathematics department.