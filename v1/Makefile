.PHONY: all clean

resume_ru: resume_ru.tex developercv.cls
	xelatex resume_ru.tex

resume_en: resume_en.tex developercv.cls
	xelatex resume_en.tex

clean:
	rm -f resume_ru.aux resume_ru.log resume_ru.out resume_en.aux resume_en.log resume_en.out

all: resume_en resume_ru
