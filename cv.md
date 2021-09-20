# Kutsak Natalia (Junior JavaScript, NodeJS, Angular) &nbsp;&nbsp;&nbsp;&nbsp; 

# ![photo](pic/nataly.jpg)  &nbsp;&nbsp;&nbsp;&nbsp;  [<img src="pic/linkedin.svg" alt="linkedin" style="width:50px; height: 50px;">](https://www.linkedin.com/in/kutsak/) [<img src="pic/github.svg" alt="GitHub" style="width:50px; height: 50px;">](https://github.com/Kutsak-Nataly)

#### WEB, SEO &nbsp;&nbsp;/&nbsp;&nbsp; Belarus, Minsk &nbsp;&nbsp;/&nbsp;&nbsp; artworknataly@gmail.com &nbsp;&nbsp;/&nbsp;&nbsp; 44 years (14.02.1977)
> +375 29 3894127 (Viber)

## Skills

*Skill / Proficiency level (maximum score 10)*

| HTML | CSS | JavaScript | Angular | NodeJS | WordPress | Bootstrap5 | SEO | Photoshop | llustarior |
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|5|5|5|5|5|6|6|7|10|10


## English

```
A2+ (passed testing in RSSChool)
```

## Education
| Date | Name | Course/Faculty |
|:--:|:--:|:--|
| 2021 | RS School (epam)  | Angular/Node JS |
| 2019 | GeekBrains  | Product Manager |
| 2011-2014 | School of business os BSU  | WEB design and programming |
| 2004-2005 | Информ-дизайн 8  | design and graphics |
| 1994-2000 | BSU (Belarusian State University)  | chemistry |
| 1992-1994 | lyceum at BSU | chemistry |

## Work experience

| Date | Organization name | Responsibilities |
|---:|:---|:---|
|2018-2020|OOO "Мирелайн"|1. Development of new directions of business<br>2. Creation of a dealer network. Consulting and training partners for the sale of our products.<br>3. Analysis of trends<br>4. Development marketing materials for the company<br>5. All responsibilities from 2013-2018 *look below* |
|2013-2018|OOO "Мирелайн"|website development [mireline](https://mireline.by/), [m-dekor](https://m-dekor.by/), [m-rezka](https://m-rezka.by/), [m-promo](https://m-promo.by/)<br>1. Website development (design, structure development, layout, WordPress)<br>2. Filling company sites (text and graphics)<br>3. SEO<br>4. Working with Yandex and Google Webmaster Tools<br>5. Working with the hosting service (mail, etc.)<br>6. Ensuring the flow of customers from the Internet|
|2009-2013|freelance|**Study, change of the type of activity**<br>1. Design of advertising layouts and layout of advertising articles (printing)<br>2. Website development (HTML, CSS, jQuery)<br>3. Writing technical specifications for website development |
|2007-2008|Publisher «Кавалер»|1. Development of advertising layouts for magazines, newspapers<br>2. Development of outdoor advertising layouts<br>3. Layout, design of books<br>4. Design: calendars, posters, booklets |
|2007-2007|Advertising agency "Кавалер"|Development of advertising products, POS materials|
|2005-2006|"СПН-Рематис"| Magazine MC - Mobile Connection (design / layout)

## Code example
```Angular
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
```


