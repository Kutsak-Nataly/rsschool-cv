utsak Natalia / (Junior JavaScript, NodeJS, Angular)
photo

github github github
WEB, SEO / Belarus, Minsk / artworknataly@gmail.com / 44 years (14.02.1977)
Skills

HTML | CSS | JavaScript | Angular | NodeJS | WordPress | Bootstrap5 | SEO | Photoshop | llustarior
English

A2+ (passed testing in RSSChool)
Education
Date 	Name 	Course/Faculty
2021 	RS School (epam) 	Angular/Node JS
2019 	GeekBrains 	Product Manager
2011-2014 	School of business os BSU 	WEB design and programming
2004-2005 	Информ-дизайн 8 	design and graphics
1994-2000 	BSU (Belarusian State University) 	chemistry
1992-1994 	lyceum at BSU 	chemistry
Work experience
Date 	Organization name 	Responsibilities
2018-2020 	OOO "Мирелайн" 	

    Development of new directions of business
    Development of new directions of business
    Creation of a dealer network. Consulting and training partners for the sale of our products.
    Analysis of trends
    4. Development marketing materials for the company
    All responsibilities from 2013-2018 look below

2018-2020 	OOO "Мирелайн" 	website development: mireline.by, m-dekor.by, m-promo.by, m-rezka.by

    Website development (design, structure development, layout, WordPress)
    Filling company sites (text and graphics)
    SEO
    Working with Yandex and Google Webmaster Tools
    Working with the hosting service (mail, etc.)
    Ensuring the flow of customers from the Internet

2009-2013 	freelance 	

    Study, change of the type of activity
    Design of advertising layouts and layout of advertising articles (printing)
    Website development (HTML, CSS, jQuery)
    Writing technical specifications for website development

2007-2008 	Publisher "Кавалер" 	

    Development of advertising layouts for magazines, newspapers
    Development of outdoor advertising layouts
    Layout, design of books
    Design: calendars, posters, booklets

2007-2007 	Advertising agency "Кавалер" 	Development of advertising products, POS materials
2005-2006 	"СПН-Рематис" 	Magazine MC - Mobile Connection (design / layout)
Code example

                
@Entity({name: 'board'})
export class Board {
    @Column({default: 'string'})
    title: string;
    @OneToMany(() => ColumnBoard, column => column.board, {cascade: ['insert', 'update', 'remove', 'soft-remove', 'recover'], eager: true})
    columns: ColumnBoard[];
    @OneToMany(() => Task, task => task.board, {cascade: ['remove']})
    tasks: Task[];
    @PrimaryGeneratedColumn('uuid')
    id?: string;
}
                
            

Kutsak Nataly / 2025 rsschool