//
//  ViewController.m
//  CourseMate
//
//  Created by michael on 17/03/2017.
//  Copyright © 2017 michael. All rights reserved.
//

#import "ViewController.h"
#import "DrawViewController.h"

@interface ViewController ()

- (IBAction)onAddTouched:(id)sender;

@end

@implementation ViewController

- (void)viewDidLoad {
    [super viewDidLoad];
    // Do any additional setup after loading the view, typically from a nib.
}


- (void)didReceiveMemoryWarning {
    [super didReceiveMemoryWarning];
    // Dispose of any resources that can be recreated.
}

- (BOOL)prefersStatusBarHidden
{
    return YES; //返回NO表示要显示，返回YES将hiden
}

#pragma IBAction

- (IBAction)onAddTouched:(id)sender {
    // push DrawViewController
    
    UIStoryboard* storyboard = [UIStoryboard storyboardWithName:@"Main" bundle:[NSBundle mainBundle]];
    DrawViewController* controller = [storyboard instantiateViewControllerWithIdentifier:@"DrawViewController"];
    
    [self presentViewController:controller animated:YES completion:nil];
        
}

@end
