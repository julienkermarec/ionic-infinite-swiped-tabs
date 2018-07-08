# ionic-3-infinite-swiped-tabs

![Screenshot](https://raw.githubusercontent.com/julienkermarec/ionic-infinite-swiped-tabs/master/screenshots/header.png)

## Tutoriel

https://blog.julienkermarec.com/ionic-3-infinite-swiped-tabs/

## Features
Infinite Tabs / Segments__
Auto-centering active segment with animation__
iOS / Android UX compatible__

## Usage
```html
<!-- TOOLBAR + SEGMENTS -->
<ion-toolbar mode="md" color="light">
  <ion-segment  #segments  mode="md" [(ngModel)]="page" color="light">
      <ion-segment-button value="0"  (click)="selectedTab(0)">
          Segment 1
      </ion-segment-button>
      <ion-segment-button value="1"  (click)="selectedTab(1)">
          Segment 2
      </ion-segment-button>
      <ion-segment-button value="2"  (click)="selectedTab(2)">
          Segment 3
      </ion-segment-button>
      <ion-segment-button value="3"  (click)="selectedTab(3)">
          Segment 4
      </ion-segment-button>
      <ion-segment-button value="4"  (click)="selectedTab(4)">
          Segment 5
      </ion-segment-button>
  </ion-segment>
</ion-toolbar>
<!-- SLIDES -->
<ion-slides #slider (ionSlideDidChange)="slideChanged()">
    <ion-slide>
        <h1>Tab 1</h1>
    </ion-slide>
    <ion-slide>
        <h1>Tab 2</h1>
    </ion-slide>
    <ion-slide>
        <h1>Tab 3</h1>
    </ion-slide>
    <ion-slide>
        <h1>Tab 4</h1>
    </ion-slide>
    <ion-slide>
        <h1>Tab 5</h1>
    </ion-slide>
</ion-slides>

```

## TODO
- [X] Ion-segment
- [X] Ion-slides
- [X] Center active segment
- [X] Animate active segment

## Info/Support

If you need support, or business inquiry contact-me :

@JulienKermarec - contact@julienkermarec.com
