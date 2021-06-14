pipeline {
    agent any
    stages {
        stage('Create PR') {
            steps {
                echo 'Create PR'
            }
        }
        stage('InSpec Profile') {
            parallel {
                stage('InSpec Profile') {
                    steps {
                        echo 'test'
                    }
                }
                stage('Inspec.yml') {
                    steps {
                        echo 'test'
                    }
                }
                stage('Controls') {
                    steps {
                        echo 'test'
                    }
                }
                stage('Libraries') {
                    steps {
                        echo 'test'
                    }
                }
                stage('Files') {
                    steps {
                        echo 'test'
                    }
                }
                stage('README.md') {
                    steps {
                        echo 'test'
                    }
                }
            }
        }
        stage('Verify inspec.yml') {
            parallel {
                stage('Verify inspec.yml') {
                    steps {
                        echo 'test'
                    }
                }
                stage('inspec check') {
                    steps {
                        echo 'test'
                    }
                }
            }
        }
        stage('Ruby Lint Check') {
            parallel {
                stage('Ruby Lint Check') {
                    steps {
                        echo 'test'
                    }
                }
                stage('Rubocop') {
                    steps {
                        echo 'test'
                    }
                }
            }
        }
        stage('Code Review') {
            steps {
                echo 'test'
            }
        }
        stage('Commit to Master') {
            steps {
                echo 'test'
            }
        }
        stage('Produce Archive') {
            parallel {
                stage('Produce Archive') {
                    steps {
                        echo 'test'
                    }
                }
                stage('inspec vendor') {
                    steps {
                        echo 'test'
                    }
                }
                stage('inspec archive') {
                    steps {
                        echo 'test'
                    }
                }
                stage('Sign the Artifact') {
                    steps {
                        echo 'test'
                    }
                }
            }
        }
        stage('Publish Artifact') {
            steps {
                echo 'test'
            }
        }
        stage('Update Artifact URLs and Versions') {
            parallel {
                stage('Update Artifact URLs and Versions') {
                    steps {
                        echo 'test'
                    }
                }
                stage('inspec vendor') {
                    steps {
                        echo 'test'
                    }
                }
                stage('inspec check') {
                    steps {
                        echo 'test'
                    }
                }
                stage('inspec archive') {
                    steps {
                        echo 'test'
                    }
                }
                stage('Sign the Artifact') {
                    steps {
                        echo 'test'
                    }
                }
            }
        }
        stage('Publish Artifact') {
            steps {
                echo 'test'
            }
        }
        stage('Produce policyfile archive as tarball and lockfile') {
            parallel {
                stage('loads all of the policyfile lock files in a directory into the Chef server') {
                    steps {
                        echo 'test'
                    }
                }
                stage('chef export POLICY_FILE -a ARCHIVE_FILE') {
                    steps {
                        echo 'test'
                    }
                }
                stage('chef push-archive POLICY_GROUP ARCHIVE_FILE') {
                    steps {
                        echo 'test'
                    }
                }
            }
        }
        stage('Publish to Artifactory') {
            steps {
                echo 'Publish to Artifactory'
            }
        }
    }
}
